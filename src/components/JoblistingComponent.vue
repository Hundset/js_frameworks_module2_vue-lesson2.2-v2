<template>
    <div class="[ row ]">
        <div class="[ col-sm-4 ]">
            <div class="[ card ]">
                <div>
                <img />
                </div>
                <div class="[ card--information ]"><br />
                    <span>Date Created: </span> <br />
                    <span>Title: </span> <br />
                    <span>Company Name: </span><br />
                    <span>Location: </span><br />
                    <span>Type: </span><br />
                    <span>Description: </span><br />
                    <span>How to apply: </span><br />
                    <span>Company Website: </span><a ref="" target="_blank">Click Here</a><br />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'JobListingComponent',
}
</script>

<style scoped>

    .card {
        border: solid 1px black;
        border-radius: 4px;
        padding: 0px 20px 30px;
        margin-top: 30px;
    }

    .card img {
        width: 100%;
        padding-top: 20px;
    }

    .card span {
        font-weight: bold;
    }

</style>