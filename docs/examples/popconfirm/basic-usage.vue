<template>
<el-popconfirm
          title="确认删除该人员吗？"
          @confirm="delPerson(scope.$index, scope.row)">
          <el-button
            size="mini"
            type="danger"
            slot="reference"
            >删除</el-button>
        </el-popconfirm>
  <el-popconfirm title="Are you sure to delete this?">
    <template #reference>
      <el-button>Delete</el-button>
    </template>
  </el-popconfirm>
</template>
