<template>
    <div class="[ row ]">
        <JobListingcomponent></JobListingcomponent>
    </div>
</template>

<script>

import JobListingcomponent from './components/JoblistingComponent.vue'

export default {
    name: 'JobListing',
    components: {
        JobListingcomponent
    }
}
</script>