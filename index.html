<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інтерактивний суд - дистанційний формат</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 10px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            max-width: 1200px;
            width: 100%;
            padding: 40px;
        }

        h1 {
            color: #333;
            margin-bottom: 10px;
            text-align: center;
        }

        .subtitle {
            color: #666;
            text-align: center;
            margin-bottom: 30px;
            font-size: 14px;
        }

        .mode-selector {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 30px;
        }

        .mode-button {
            padding: 20px;
            border: 2px solid #ddd;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            background: #f9f9f9;
            font-size: 16px;
            font-weight: bold;
            color: #333;
        }

        .mode-button:hover {
            border-color: #667eea;
            background: #f0f0ff;
        }

        .mode-button.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }

        .section {
            display: none;
        }

        .section.active {
            display: block;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: bold;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 14px;
            font-family: inherit;
        }

        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 5px rgba(102, 126, 234, 0.3);
        }

        .button {
            background: #667eea;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: background 0.3s ease;
            width: 100%;
        }

        .button:hover {
            background: #764ba2;
        }

        .button.secondary {
            background: #ddd;
            color: #333;
            margin-top: 10px;
        }

        .button.secondary:hover {
            background: #ccc;
        }

        .room-code {
            background: #f0f0ff;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
            text-align: center;
        }

        .room-code-label {
            color: #666;
            font-size: 14px;
        }

        .room-code-value {
            font-size: 32px;
            font-weight: bold;
            color: #667eea;
            font-family: 'Courier New', monospace;
            margin: 10px 0;
        }

        .copy-button {
            background: #667eea;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 12px;
        }

        .copy-button:hover {
            background: #764ba2;
        }

        .roles-list {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
        }

        .role-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px;
            background: white;
            border-radius: 5px;
            margin-bottom: 10px;
            border-left: 4px solid #667eea;
        }

        .role-name {
            font-weight: bold;
            color: #333;
        }

        .role-student {
            color: #666;
            font-size: 14px;
        }

        .role-actions {
            display: flex;
            gap: 10px;
        }

        .role-button {
            padding: 5px 10px;
            font-size: 12px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            background: #667eea;
            color: white;
        }

        .role-button:hover {
            background: #764ba2;
        }

        .speech-area {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
            border: 2px dashed #ddd;
        }

        .court-status {
            background: #e8f4f8;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            border-left: 4px solid #667eea;
        }

        .status-text {
            color: #333;
            font-weight: bold;
        }

        .messages {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            height: 300px;
            overflow-y: auto;
            margin-bottom: 15px;
        }

        .message {
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            background: #f0f0f0;
            border-left: 4px solid #667eea;
        }

        .message-speaker {
            font-weight: bold;
            color: #667eea;
        }

        .message-text {
            color: #333;
            margin-top: 5px;
        }

        .message-time {
            font-size: 12px;
            color: #999;
            margin-top: 5px;
        }

        .error {
            background: #fee;
            color: #c33;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }

        .success {
            background: #efe;
            color: #3c3;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }

        @media (max-width: 768px) {
            .mode-selector {
                grid-template-columns: 1fr;
            }

            .container {
                padding: 20px;
            }

            h1 {
                font-size: 20px;
            }
        }

        .logout-button {
            position: absolute;
            top: 20px;
            right: 20px;
        }

        .room-code-copy {
            display: flex;
            justify-content: center;
            gap: 10px;
            align-items: center;
        }

        .divider {
            border-top: 1px solid #ddd;
            margin: 20px 0;
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        @media (max-width: 768px) {
            .grid-2 {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <button class="button secondary logout-button" id="logoutBtn" style="display: none; width: 150px;" onclick="logout()">Вийти</button>

        <div id="setupSection">
            <h1>🏛️ Інтерактивний суд</h1>
            <p class="subtitle">Дистанційний формат для рольової гри</p>

            <div class="mode-selector">
                <button class="mode-button active" onclick="selectMode('teacher')">👨‍⚖️ Вчитель</button>
                <button class="mode-button" onclick="selectMode('student')">👨‍🎓 Учень</button>
            </div>

            <div id="teacherSetup" class="section active">
                <h2>Кабінет вчителя</h2>
                <div class="form-group">
                    <label>Ваше ім'я:</label>
                    <input type="text" id="teacherName" placeholder="Введіть ваше ім'я">
                </div>
                <div class="form-group">
                    <label>Назва судового процесу:</label>
                    <input type="text" id="caseTitle" placeholder="Наприклад: Справа № 1">
                </div>
                <button class="button" onclick="createRoom()">Створити кімнату</button>
            </div>

            <div id="studentSetup" class="section">
                <h2>Приєднання до судового засідання</h2>
                <div class="form-group">
                    <label>Ваше ім'я:</label>
                    <input type="text" id="studentName" placeholder="Введіть ваше ім'я">
                </div>
                <div class="form-group">
                    <label>Код кімнати:</label>
                    <input type="text" id="roomCode" placeholder="Введіть 6-значний код">
                </div>
                <button class="button" onclick="joinRoom()">Приєднатися</button>
            </div>
        </div>

        <div id="teacherDashboard" class="section">
            <button class="button secondary" onclick="logout()" style="margin-bottom: 20px;">← Вийти</button>
            <h2>Кабінет вчителя</h2>
            <div id="teacherMessageContainer"></div>

            <div class="room-code">
                <div class="room-code-label">Код кімнати судового засідання:</div>
                <div class="room-code-value" id="displayRoomCode">-</div>
                <div class="room-code-copy">
                    <button class="copy-button" onclick="copyRoomCode()">Скопіювати</button>
                </div>
            </div>

            <h3>Розподіл ролей</h3>
            <div class="grid-2">
                <div>
                    <label>Додайте ролі для судового процесу:</label>
                    <input type="text" id="roleName" placeholder="Наприклад: Суддя">
                    <button class="button" onclick="addRole()" style="margin-top: 10px;">Додати роль</button>
                </div>
                <div class="roles-list" id="rolesList">
                    <div style="color: #999; text-align: center;">Ролі будуть з'являтися тут</div>
                </div>
            </div>

            <div class="divider"></div>

            <h3>Учні в кімнаті</h3>
            <div class="roles-list" id="studentsList">
                <div style="color: #999; text-align: center;">Учні будуть приєднуватися сюди</div>
            </div>

            <div class="divider"></div>

            <h3>Керування судовим засіданням</h3>
            <div class="form-group">
                <label>Статус засідання:</label>
                <select id="courtStatus" onchange="updateCourtStatus()">
                    <option value="waiting">Очікування учнів</option>
                    <option value="opening">Відкриття засідання</option>
                    <option value="active">Активне засідання</option>
                    <option value="closing">Завершення засідання</option>
                </select>
            </div>

            <div class="form-group">
                <label>Повідомлення до учнів:</label>
                <textarea id="teacherMessageInput" placeholder="Введіть повідомлення для класу" rows="3"></textarea>
                <button class="button" onclick="sendTeacherMessage()">Відправити</button>
            </div>
        </div>

        <div id="studentDashboard" class="section">
            <button class="button secondary" onclick="logout()" style="margin-bottom: 20px;">← Вийти</button>
            <h2>Судове засідання</h2>

            <div class="court-status">
                <div class="status-text">Ваша роль: <span id="studentRole">-</span></div>
                <div style="color: #666; margin-top: 5px;">Статус: <span id="sessionStatus">Очікування</span></div>
            </div>

            <div class="speech-area">
                <h3>Виступ у суді</h3>
                <div class="form-group">
                    <label>Ваше повідомлення:</label>
                    <textarea id="studentSpeech" placeholder="Виголосіть вашу промову, запитання або відповідь..." rows="4"></textarea>
                </div>
                <button class="button" onclick="sendSpeech()">Виголосити в суді</button>
            </div>

            <div class="divider"></div>

            <h3>Судова залік</h3>
            <div class="messages" id="courtMessages">
                <div style="color: #999; text-align: center; padding: 20px;">Виступи будуть з'являтися тут</div>
            </div>

            <div class="form-group">
                <label>Об'єкти розгляду:</label>
                <select id="evidenceList">
                    <option value="">-- Виберіть докази --</option>
                </select>
            </div>
        </div>
    </div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.0/firebase-app.js";
        import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.7.0/firebase-analytics.js";
        import {
            getFirestore,
            doc,
            setDoc,
            updateDoc,
            arrayUnion,
            onSnapshot,
            getDoc
        } from "https://www.gstatic.com/firebasejs/10.7.0/firebase-firestore.js";

        // Firebase конфігурація
        const firebaseConfig = {
            apiKey: "AIzaSyB9e-OOas_4xCoNTQPYoJA9gXltB6EzSnw",
            authDomain: "interaction9loa.firebaseapp.com",
            projectId: "interaction9loa",
            storageBucket: "interaction9loa.firebasestorage.app",
            messagingSenderId: "228660116445",
            appId: "1:228660116445:web:0d729a05494c2303659434",
            measurementId: "G-4HJ2833RMX"
        };

        const app = initializeApp(firebaseConfig);
        const analytics = getAnalytics(app);
        const db = getFirestore(app);

        let userRole = null;
        let userName = null;
        let roomCode = null;
        let currentRoom = null;
        let teacherUID = null;

        function selectMode(mode) {
            const buttons = document.querySelectorAll('.mode-button');
            buttons.forEach(btn => btn.classList.remove('active'));
            if (mode === 'teacher') {
                buttons[0].classList.add('active');
                document.getElementById('teacherSetup').classList.add('active');
                document.getElementById('studentSetup').classList.remove('active');
            } else {
                buttons[1].classList.add('active');
                document.getElementById('teacherSetup').classList.remove('active');
                document.getElementById('studentSetup').classList.add('active');
            }
        }

        function generateRoomCode() {
            return Math.random().toString(36).substring(2, 8).toUpperCase();
        }

        async function createRoom() {
            const teacherName = document.getElementById('teacherName').value;
            const caseTitle = document.getElementById('caseTitle').value;

            if (!teacherName || !caseTitle) {
                alert('Будь ласка, заповніть усі поля');
                return;
            }

            userRole = 'teacher';
            userName = teacherName;
            roomCode = generateRoomCode();
            teacherUID = 'teacher_' + Date.now();

            try {
                await setDoc(doc(db, 'rooms', roomCode), {
                    code: roomCode,
                    teacherName,
                    teacherUID,
                    caseTitle,
                    createdAt: new Date(),
                    status: 'waiting',
                    roles: [],
                    students: [],
                    messages: []
                });

                showTeacherDashboard();
            } catch (error) {
                alert('Помилка при створенні кімнати: ' + error.message);
            }
        }

        async function joinRoom() {
            const studentName = document.getElementById('studentName').value;
            const inputRoomCode = document.getElementById('roomCode').value.toUpperCase();

            if (!studentName || !inputRoomCode) {
                alert('Будь ласка, заповніть усі поля');
                return;
            }

            try {
                const roomRef = doc(db, 'rooms', inputRoomCode);
                const roomDoc = await getDoc(roomRef);

                if (!roomDoc.exists()) {
                    alert('Кімната не знайдена. Перевірте код');
                    return;
                }

                userRole = 'student';
                userName = studentName;
                roomCode = inputRoomCode;

                const studentData = {
                    name: studentName,
                    uid: 'student_' + Date.now(),
                    joinedAt: new Date(),
                    role: null
                };

                await updateDoc(roomRef, {
                    students: arrayUnion(studentData)
                });

                showStudentDashboard();
            } catch (error) {
                alert('Помилка при приєднанні: ' + error.message);
            }
        }

        function showTeacherDashboard() {
            document.getElementById('setupSection').classList.remove('active');
            document.getElementById('teacherDashboard').classList.add('active');
            document.getElementById('studentDashboard').classList.remove('active');
            document.getElementById('logoutBtn').style.display = 'block';
            document.getElementById('displayRoomCode').textContent = roomCode;
            listenToTeacherUpdates();
        }

        function showStudentDashboard() {
            document.getElementById('setupSection').classList.remove('active');
            document.getElementById('teacherDashboard').classList.remove('active');
            document.getElementById('studentDashboard').classList.add('active');
            document.getElementById('logoutBtn').style.display = 'block';
            listenToStudentUpdates();
        }

        async function addRole() {
            const roleName = document.getElementById('roleName').value;
            if (!roleName) {
                alert('Введіть назву ролі');
                return;
            }

            try {
                const newRole = {
                    id: 'role_' + Date.now(),
                    name: roleName,
                    assignedTo: null
                };

                await updateDoc(doc(db, 'rooms', roomCode), {
                    roles: arrayUnion(newRole)
                });

                document.getElementById('roleName').value = '';
            } catch (error) {
                alert('Помилка при додаванні ролі: ' + error.message);
            }
        }

        function listenToTeacherUpdates() {
            const roomRef = doc(db, 'rooms', roomCode);
            onSnapshot(roomRef, snapshot => {
                if (snapshot.exists()) {
                    const data = snapshot.data();
                    updateRolesList(data.roles || []);
                    updateStudentsList(data.students || []);
                }
            });
        }

        function listenToStudentUpdates() {
            const roomRef = doc(db, 'rooms', roomCode);
            onSnapshot(roomRef, snapshot => {
                if (snapshot.exists()) {
                    const data = snapshot.data();
                    document.getElementById('sessionStatus').textContent =
                        data.status === 'waiting' ? 'Очікування' :
                        data.status === 'opening' ? 'Відкриття' :
                        data.status === 'active' ? 'Активне' : 'Завершення';

                    updateCourMessages(data.messages || []);
                }
            });
        }

        function updateRolesList(roles) {
            const rolesList = document.getElementById('rolesList');
            if (roles.length === 0) {
                rolesList.innerHTML = '<div style="color: #999; text-align: center;">Ролі будуть з\'являтися тут</div>';
                return;
            }

            rolesList.innerHTML = roles.map(role => `
                <div class="role-item">
                    <div>
                        <div class="role-name">${role.name}</div>
                        <div class="role-student">${role.assignedTo ? 'Призначена: ' + role.assignedTo : 'Не призначена'}</div>
                    </div>
                    <div class="role-actions">
                        <button class="role-button" onclick="deleteRole('${role.id}')">Видалити</button>
                    </div>
                </div>
            `).join('');
        }

        function updateStudentsList(students) {
            const studentsList = document.getElementById('studentsList');
            if (students.length === 0) {
                studentsList.innerHTML = '<div style="color: #999; text-align: center;">Учні будуть приєднуватися сюди</div>';
                return;
            }

            studentsList.innerHTML = students.map(student => `
                <div class="role-item">
                    <div>
                        <div class="role-name">${student.name}</div>
                        <div class="role-student">${student.role ? 'Роль: ' + student.role : 'Роль не призначена'}</div>
                    </div>
                </div>
            `).join('');
        }

        function updateCourMessages(messages) {
            const messagesDiv = document.getElementById('courtMessages');
            if (messages.length === 0) {
                messagesDiv.innerHTML = '<div style="color: #999; text-align: center; padding: 20px;">Виступи будуть з\'являтися тут</div>';
                return;
            }

            messagesDiv.innerHTML = messages.map(msg => `
                <div class="message">
                    <div class="message-speaker">${msg.speaker}</div>
                    <div class="message-text">${msg.text}</div>
                    <div class="message-time">${new Date(msg.timestamp).toLocaleTimeString('uk-UA')}</div>
                </div>
            `).join('');

            messagesDiv.scrollTop = messagesDiv.scrollHeight;
        }

        async function sendSpeech() {
            const speech = document.getElementById('studentSpeech').value;
            if (!speech) {
                alert('Введіть ваше повідомлення');
                return;
            }

            try {
                const newMessage = {
                    speaker: userName,
                    role: 'Student',
                    text: speech,
                    timestamp: new Date()
                };

                await updateDoc(doc(db, 'rooms', roomCode), {
                    messages: arrayUnion(newMessage)
                });

                document.getElementById('studentSpeech').value = '';
            } catch (error) {
                alert('Помилка при відправленні: ' + error.message);
            }
        }

        async function deleteRole(roleId) {
            try {
                const roomRef = doc(db, 'rooms', roomCode);
                const roomDoc = await getDoc(roomRef);
                const roles = roomDoc.data()?.roles || [];
                const updatedRoles = roles.filter(r => r.id !== roleId);
                await updateDoc(roomRef, { roles: updatedRoles });
            } catch (error) {
                alert('Помилка при видаленні: ' + error.message);
            }
        }

        async function updateCourtStatus() {
            const status = document.getElementById('courtStatus').value;
            try {
                await updateDoc(doc(db, 'rooms', roomCode), { status });
            } catch (error) {
                alert('Помилка при оновленні статусу: ' + error.message);
            }
        }

        async function sendTeacherMessage() {
            const message = document.getElementById('teacherMessageInput').value;
            if (!message) {
                alert('Введіть повідомлення');
                return;
            }

            try {
                const newMessage = {
                    speaker: userName + ' (Вчитель)',
                    role: 'Teacher',
                    text: message,
                    timestamp: new Date()
                };

                await updateDoc(doc(db, 'rooms', roomCode), {
                    messages: arrayUnion(newMessage)
                });

                document.getElementById('teacherMessageInput').value = '';
            } catch (error) {
                alert('Помилка при відправленні: ' + error.message);
            }
        }

        function copyRoomCode() {
            navigator.clipboard.writeText(roomCode).then(() => {
                alert('Код кімнати скопійовано: ' + roomCode);
            });
        }

        function logout() {
            userRole = null;
            userName = null;
            roomCode = null;
            currentRoom = null;
            teacherUID = null;

            document.getElementById('setupSection').classList.add('active');
            document.getElementById('teacherDashboard').classList.remove('active');
            document.getElementById('studentDashboard').classList.remove('active');
            document.getElementById('logoutBtn').style.display = 'none';

            document.getElementById('teacherName').value = '';
            document.getElementById('caseTitle').value = '';
            document.getElementById('studentName').value = '';
            document.getElementById('roomCode').value = '';
            document.getElementById('studentSpeech').value = '';
            document.getElementById('teacherMessageInput').value = '';
        }

        document.addEventListener('DOMContentLoaded', function () {
            selectMode('teacher');
        });

        window.selectMode = selectMode;
        window.createRoom = createRoom;
        window.joinRoom = joinRoom;
        window.addRole = addRole;
        window.deleteRole = deleteRole;
        window.updateCourtStatus = updateCourtStatus;
        window.sendTeacherMessage = sendTeacherMessage;
        window.sendSpeech = sendSpeech;
        window.copyRoomCode = copyRoomCode;
        window.logout = logout;
    </script>
</body>
</html>
