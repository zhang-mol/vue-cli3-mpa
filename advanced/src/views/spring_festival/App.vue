<template>
    <div>新年好!!!2019春节活动 {{ date }}123123</div>
</template>

<script>
import { uniqueArr } from '@/js/utils'
export default {
    data () {
        return {
            date: new Date()
        }
    },

    methods: {
        unique (arr) {
            return uniqueArr(arr)
        }
    }
}
</script>
