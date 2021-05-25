<template>
    <div>
        <input v-model="name"/>
        <input v-model="info.city"/>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: '1',
            info: {
                city: '2'
            }
        }
    },
    watch: {
        name(val, oldVal) {
            // eslint-disable-next-line
            console.log('watch name', val, oldVal) // 值类型，可正常拿到 val 和 oldVal
        },
        info: {
            handler(val, oldVal) {
                // eslint-disable-next-line
                console.log('watch info', val, oldVal) 
                // 引用类型，拿不到 oldVal 。因为指针相同，此时已经指向了新的 val
            },
            deep: true // 深度监听
        }
    }
}
</script>