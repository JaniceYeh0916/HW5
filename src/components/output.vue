<template>
    <body>
    <div id="app">
        <button class="showBtn">Show Data</button>
        <table>
            <thead>
            <tr>
                <th>Year</th>
                <th>Price (元 / 度)</th>
            </tr>
            </thead>
            <tbody>
            </tbody>
        </table>
    </div>
    </body>
</template>

<script>
export default {

}
</script>

<style scoped>
body {
    zoom: 1;
    background: #87CEEF;
    background-size: cover;
    letter-spacing: .01em;
    font-family: Noto Sans TC, Segoe UI Emoji;
}

#app {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.showBtn {
    width: 25%;
    height: 40px;
    background-color: #DCDCDC;
    color: #000000;
    padding: 12px 20px;
    margin-top: 5px;
    border: none;
    cursor: pointer;
    opacity: 0.9;
    border-radius: 10px;
}

table {
    text-align: center;
    margin-top: 20px;
    width: 80%;
    font-size: 20px;

    border: 5px white double;
    table-layout: fixed;
    border-collapse: collapse;
}

th {
    padding: 10px;
    border: 1px solid #FFFFFF;
}

td {
    border:1px solid #FFFFFF;
    padding:5px;
}
</style>