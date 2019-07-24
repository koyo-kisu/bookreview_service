<template>
    <div>
        <LoginForm />
    </div>
</template>

<style>

</style>


<script>
import LoginForm from '~/pages/LoginForm.vue';
import RegisterForm from '~/pages/RegisterForm.vue';
import LoginCheck from '~/pages/LoginCheck.vue';
import LoginFinish from '~/pages/LoginFinish.vue';

export default {
    name: 'login',
    components: {
        LoginForm,
        RegisterForm,
        LoginCheck,
        LoginFinish,
    }
}
</script>
