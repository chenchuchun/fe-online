<template>
    <div class="home">
        <el-row>
            <el-col :span="2">
                <OrgTree  class="orgtree"/>
            </el-col>
            <el-col :span="20">
                <UserTable class="usertable"/>
            </el-col>
        </el-row>
    </div>
</template>
<script lang="ts" name="home" setup>
import OrgTree from '../../component/orgTree/index.vue'
import UserTable from '../../component/userTable/index.vue'

</script>
<style lang="scss" scoped>
.home{
    width: 100%;
}

</style>