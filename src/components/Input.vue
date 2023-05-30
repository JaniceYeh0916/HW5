<template>
    <body>
    <div class="webTitle">
        <h1>歷年平均電價</h1>
    </div>
    <div class="input">
        <form id="electricity" action="http://localhost:3000/api" method="post">
            <label for="year" class="year">Year :</label>
            <input type="text" id="year" name="year">
            <label for="price" class="price">Price :</label>
            <input type="text" id="price" name="price">
            <button type="submit" class="submitBtn">Submit</button>
        </form>
    </div>
    </body>

</template>

<script>
export default {}
</script>

<style scoped>
body {
    zoom: 1;
    background: #87CEEF;
    background-size: cover;
    letter-spacing: .01em;
    font-family: Noto Sans TC, Segoe UI Emoji;
}

.webTitle {
    display: flex;
    justify-content: center;
    color: white;
}

.input {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 120px;
}

form {
    display: flex;
    align-items: center;
    justify-content: center;
}

.year, .price {
    display: flex;
    margin-top: 15px;
    margin-right: 15px;
    margin-left: 20px;
    width: 70px;
    font-size: 20px;
}

#year, #price {
    display: flex;
    height: 25px;
    width: 200px;
    margin-top: 20px;
    border-radius: 10px;
    border: none;
}

.submitBtn {
    width: 25%;
    height: 40px;
    background-color: #DCDCDC;
    color: #000000;
    padding: 12px 20px;
    margin-top: 20px;
    margin-left: 30px;
    border: none;
    cursor: pointer;
    opacity: 0.9;
    border-radius: 10px;
}
</style>