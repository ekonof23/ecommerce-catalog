<template>
    <body class="body">
        <div class="outer-margin">
            <!-- Konten men section -->
            <div class="unavailable-section">

                <div class="rectangle5">

                </div>
                <div class="rectangle-7">
                    <div class="sad-face">
                        <div class="vector-14">
                            <svg width="196" height="53" viewBox="0 0 196 53" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path d="M194 35.3236C91.324 50.4142 27.2183 25.3956 8 11" stroke="black"
                                    stroke-opacity="0.1" stroke-width="25" />
                            </svg>
                        </div>
                        <div class="vector-13">
                            <svg width="196" height="52" viewBox="0 0 196 52" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path d="M2 34.5C104.4 49.7 168.333 24.5 187.5 10" stroke="black" stroke-opacity="0.1"
                                    stroke-width="25" />
                            </svg>
                        </div>
                    </div>

                    <div class="sad-eye">
                        <svg width="442" height="107" viewBox="0 0 442 107" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M0.295454 53.0852C0.295454 38.5795 5.49006 26.1321 15.8793 15.7429C26.2685 5.3537 38.7159 0.159094 53.2216 0.159094C67.7273 0.159094 80.1747 5.3537 90.5639 15.7429C100.953 26.1321 106.148 38.5795 106.148 53.0852C106.148 67.5909 100.953 80.0384 90.5639 90.4276C80.1747 100.817 67.7273 106.011 53.2216 106.011C43.6165 106.011 34.7955 103.561 26.7585 98.6605C18.7216 93.956 12.2528 87.5852 7.35227 79.5483C2.64773 71.7074 0.295454 62.8864 0.295454 53.0852ZM335.494 53.0852C335.494 38.5795 340.689 26.1321 351.078 15.7429C361.467 5.3537 373.915 0.159094 388.42 0.159094C402.926 0.159094 415.374 5.3537 425.763 15.7429C436.152 26.1321 441.347 38.5795 441.347 53.0852C441.347 67.5909 436.152 80.0384 425.763 90.4276C415.374 100.817 402.926 106.011 388.42 106.011C378.815 106.011 369.994 103.561 361.957 98.6605C353.92 93.956 347.452 87.5852 342.551 79.5483C337.847 71.7074 335.494 62.8864 335.494 53.0852Z"
                                fill="black" fill-opacity="0.1" />
                        </svg>
                    </div>
                    <div class="sad-mouth">
                        <svg width="754" height="174" viewBox="0 0 754 174" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M377.045 0.21023C451.142 0.21023 519.26 9.81534 581.399 29.0256C643.734 48.4318 701.071 76.071 753.409 111.943V173.102C734.003 158.989 710.088 145.757 681.665 133.408C653.438 121.254 622.368 110.571 588.456 101.358C554.74 92.1449 519.848 84.892 483.78 79.5994C447.712 74.5028 412.134 71.9546 377.045 71.9546C330.392 71.9546 283.053 76.4631 235.027 85.4801C187.001 94.4972 142.406 106.651 101.241 121.94C60.0767 137.23 26.5568 154.284 0.681811 173.102V111.943C53.0199 76.071 110.259 48.4318 172.398 29.0256C234.733 9.81534 302.949 0.21023 377.045 0.21023Z"
                                fill="black" fill-opacity="0.1" />
                        </svg>
                    </div>
                    <div class="this-product">
                        This product is unavailable to show
                    </div>
                    <div class="rectangle-3">
                        <div class="next-product">
                            Next product
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </body>
</template>

<script>
export default {
    // Logika komponen men section
    name: 'Unavailable'
}
</script>

<style scoped>
* {
    margin: auto;
    padding: auto;

}

.outer-margin::before {
    content: "";
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: black;
    z-index: -1;
}

.unavailable-section {
    position: relative;
    width: 1283px;
    height: 832px;
    background: #FFFFFF;
}

.rectangle5 {
    position: absolute;
    width: 1283px;
    height: 548px;
    left: 0;
    top: 0px;
    background: #D8D7D7;
    ;
}

/* This product is unavailable to show */
.this-product {
    position: absolute;
    width: 332px;
    height: 24px;
    left: 351px;
    top: 246px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 24px;
    color: #000000;

}

/* Next product */
.next-product {
    position: absolute;
    width: 127px;
    height: 24px;
    left: 169px;
    top: 9px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 24px;
    color: #3F3F3F;

}

/* Rectangle 3 */
.rectangle-3 {
    position: absolute;
    box-sizing: border-box;
    width: 465px;
    height: 42px;
    left: 284px;
    top: 283px;
    background: #FFFFFF;
    border: 3px solid #000000;
    border-radius: 4px;
}

/* sad-face */
.sad-face {
    position: absolute;
    width: 1028px;
    height: 439px;
    left: 61px;
    top: 107px;
}

/* sad-face */
.sad-mouth {
    position: absolute;
    width: 1028px;
    height: 439px;
    left: 0;
    top: 335px;
}

/* Vector 14 */
.vector-14 {
    position: absolute;
    width: 186px;
    height: 29px;
    left: 553px;
    top: 14px;
}

/* Vector 13 */
.vector-13 {
    position: absolute;
    width: 186px;
    height: 29px;
    left: 107px;
    top: 14px;
}

/* : */
.sad-eye {
    position: absolute;
    width: 229px;
    height: 1002px;
    left: 267px;
    top: 170px;
}

/* Rectangle 7 */
.rectangle-7 {
    position: absolute;
    width: 1034px;
    height: 580px;
    left: 147px;
    top: 126px;
    background: #FFFFFF;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
}
</style>