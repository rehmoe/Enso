<template>
    <date-field time-only
        v-bind="$attrs"
        v-on="$listeners"/>
</template>

<script>

import DateField from './DateField.vue';

export default {
    name: 'TimeField',

    components: { DateField },
};

</script>
