<script type="text/javascript">
    myCnt = 3;

    // URLのリスト
    myTable = new Array(
        "https://docs.google.com/forms/d/e/1FAIpQLSeH9eB5jiVsOU5YsRd7wCsVyyB_Ql-6YuavwQ66-rT-qeoHOA/viewform?usp=header",
        "https://www.deepl.com/ja/translator",
        "https://mightyace.co.jp/2021/09/18/column3465/"
    );

    // ランダムに選んで飛ばす関数
    function myRndLink() {
        myRnd = Math.floor(Math.random() * myCnt);
        location.href = myTable[myRnd];
    }
</script>

<form>
    <input type="button" value="ランダムに移動" onclick="myRndLink()">
</form>
