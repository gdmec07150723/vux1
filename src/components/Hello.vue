  <template>
    <div>
     <span class="title">
      欢迎登录
     </span>
     <divider>Vue Vux</divider>
     <Group>
        <XInput title="账号" v-model='account' placeholder='账号' type='text'>
        </XInput>
     </Group>
     <x-innput title="密码" v-model='password' placeholder='密码' type='password'/>
  <XButton tyoe="primary" action-type="button">登录</XButton> 
  
    </div>
  </template>

  <script>
  import { Divider, Group, XInput, XButton } from 'vux'
  export default {
    components: {
      Divider,
      Group,
      XInput,
      XButton
    },
    data () {
      return {
        account: '',
        password: ''
      }
    }
  }
</script>
