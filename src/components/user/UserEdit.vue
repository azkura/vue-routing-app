<template>
    <div>
        <h3>Edit the User</h3>
        <p>Locale: {{ $route.query.locale }}</p>
        <p>Analitycs: {{ $route.query.q }}</p>
        <hr>
        <button class="btn btn-primary">Confirm</button>
        <div style="height: 700px"></div>
        <p id="data">Some Extra Data</p>     
    </div>
</template>