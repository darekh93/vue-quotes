<template>
    <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="panel panel-defailt">
            <div class="panel-body quote">
                <slot></slot>
            </div>
        </div>
    </div>
</template>

<script>
    
</script>

<style>
    .panel-body {
        font-size: 24px;
        color: #6e6e6e;
        border: 1px solid lightgray;
    }

    .quote {
        cursor: pointer;
    }

    .quote:hover {
        background-color: #ffe2e2;
    }
</style>

