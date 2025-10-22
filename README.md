<script type="text/javascript">
    myCnt = 4;

    // URLのリスト
    myTable = new Array(
        "https://docs.google.com/forms/d/e/1FAIpQLSeH9eB5jiVsOU5YsRd7wCsVyyB_Ql-6YuavwQ66-rT-qeoHOA/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLScgXWmxzSALaUQBUD-79ph52nuX70bdmsX-Ig0KIdcxhPkMEw/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSeIlxTdhit4mPxIYwxWT1rVOYqGkBOCs2iAubFkIN8nazCTig/viewform?usp=header",
　　　　"https://docs.google.com/forms/d/e/1FAIpQLSc1xA8Nlrl06HX_1ek5uBS_n_Zknqn2Wl6teiFSdp9-4XBNPw/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSexd4bIA8mOzaTXS3OIqcllyYXQuPfQTi1Vsc0yULYngSv-tQ/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSciRGu3rHSdaQoZCiVGhFxdNDUAnZRCNfuEDYu3NK--vd6gjQ/viewform?usp=publish-editor",
        
 "https://docs.google.com/forms/d/e/1FAIpQLSfiX7h5FsG3JkF_Td-n4bSczJOyaiZGdG10Tf9AzFM5b8Rnow/viewform?usp=publish-editor",
        
"https://docs.google.com/forms/d/e/1FAIpQLSdahq1aYXpO-UPlxg5CeCK3_QERQZ3zPZuwp14s7eneBN6CjQ/viewform?usp=publish-editor"
    );

    // ランダムに選んで飛ばす関数
    function myRndLink() {
        myRnd = Math.floor(Math.random() * myCnt);
        location.href = myTable[myRnd];
    }
</script>

<form>
    <input type="button" value="ここをクリック" onclick="myRndLink()">
</form>
