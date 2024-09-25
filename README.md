# -4

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>세미나 등록</title>
    <link rel="stylesheet" href="styles.css">
    <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    padding: 20px;
}

header {
    text-align: center;
    background: #007BFF;
    color: white;
    padding: 20px 0;
}

.event-details {
    background: white;
    margin: 20px 0;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.details {
    display: flex;
    justify-content: space-around;
    text-align: center;
    padding: 20px;
}

.details div {
    flex: 1;
}

h2 {
    margin-bottom: 20px;
    text-align: center;
}

.registration {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

form {
    display: grid;
    grid-template-columns: 1fr;
    gap: 10px;
}

input[type="text"],
input[type="email"] {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.cta-button {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

.cta-button:hover {
    background-color: #0056b3;
}

footer {
    text-align: center;
    margin-top: 20px;
    color: #555;
}

      </style>
</head>
<body>
    <header>
        <h1>2024 시크릿 주 주 세미나</h1>
        <p>다가오는 비즈니스 트라이앵글</p>
    </header>

    <section class="event-details">
        <h2>이벤트 정보</h2>
        <div class="details">
            <div class="date">
                <h3>일정</h3>
                <p>2024년 09월 24일 (토)</p>
            </div>
            <div class="location">
                <h3>장소</h3>
                <p>일본 신짱구 집 앞 마당</p>
            </div>
            <div class="speakers">
                <h3>김연자</h3>
                <ul>
                    <li>김연자 교수 - 미래 기술 아모르파티 </li>
                    <li>강성태 대표 - 글로벌 마켓</li>
                    <li>나훈아 이사 - AI와 함께 라면</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="registration">
        <h2>세미나 등록</h2>
        <form action="#" method="POST">
            <label for="name">이름:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">이메일:</label>
            <input type="email" id="email" name="email" required>

            <button type="submit" class="cta-button">세미나 등록하기</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 시크릿 주 주 세미나 주최</p>
    </footer>
</body>
</html>
