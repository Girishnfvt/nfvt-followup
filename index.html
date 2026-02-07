<!DOCTYPE html>
<html lang="ta">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NFVT Team Followup - Final</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf-autotable/3.5.25/jspdf.plugin.autotable.min.js"></script>

    <style>
        body { font-family: 'Inter', sans-serif; background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); min-height: 100vh; margin: 0; padding: 20px; padding-bottom: 100px; }
        #loginOverlay { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: #1a202c; display: flex; align-items: center; justify-content: center; z-index: 2000; }
        .login-box { background: white; padding: 30px; border-radius: 12px; text-align: center; box-shadow: 0 10px 25px rgba(0,0,0,0.2); }
        .login-box input { display: block; width: 250px; margin: 10px auto; padding: 10px; border: 1px solid #cbd5e0; border-radius: 6px; }
        .login-btn { background: #2563eb; color: white; border: none; padding: 10px 20px; border-radius: 6px; font-weight: 700; cursor: pointer; }
        .container { max-width: 1200px; margin: auto; background: white; padding: 30px; border-radius: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); position: relative; display: none; }
        .header-section { text-align: center; margin-bottom: 25px; }
        .team-logo { max-width: 150px; height: auto; border-radius: 10px; margin-bottom: 10px; }
        h1 { font-size: 22px; color: #1a202c; font-weight: 700; margin: 0; }
        .floating-logo { position: fixed; bottom: 20px; right: 20px; width: 80px; height: auto; z-index: 1000; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.2); border: 2px solid white; }
        .leader-card-small { position: fixed; bottom: 20px; left: 20px; background: white; padding: 8px; border-radius: 15px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); display: flex; align-items: center; gap: 10px; z-index: 1000; border: 1.5px solid #ec4899; width: auto; max-width: 220px; }
        .profile-circle-small { width: 50px; height: 50px; border-radius: 50%; border: 2px solid #ec4899; overflow: hidden; flex-shrink: 0; background: #fff1f2; }
        .profile-circle-small img { width: 100%; height: 100%; object-fit: cover; object-position: 50% 0%; transform: scale(1.1); }
        .leader-info-small { display: flex; flex-direction: column; }
        .leader-name-small { font-weight: 700; font-size: 13px; margin: 0; color: #1e293b; }
        .leader-rank-small { font-size: 8px; color: #be185d; font-weight: 800; text-transform: uppercase; margin: 1px 0; }
        .contact-btn-small { color: #ec4899; text-decoration: none; font-size: 10px; font-weight: 700; display: flex; align-items: center; gap: 4px; }
        .form-section { background: #f8fafc; padding: 20px; border-radius: 12px; border: 1px solid #e2e8f0; margin-bottom: 25px; }
        .grid-form { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 12px; }
        .input-group label { display: block; font-size: 11px; font-weight: 700; color: #718096; margin-bottom: 5px; text-transform: uppercase; }
        input, select { width: 100%; padding: 10px; border: 1px solid #cbd5e0; border-radius: 6px; box-sizing: border-box; font-size: 14px; }
        .add-btn { background: #2563eb; color: white; border: none; padding: 11px; border-radius: 6px; font-weight: 600; cursor: pointer; transition: 0.2s; align-self: flex-end; }
        .high-pv { background-color: #dcfce7 !important; border-left: 5px solid #16a34a; } 
        .no-consistency { background-color: #fee2e2 !important; border-left: 5px solid #ef4444; } 
        .achiever-row { background-color: #fffbeb !important; border-left: 5px solid #f59e0b; } 
        .status-red { color: #dc2626 !important; font-weight: 800; background-color: #fef2f2; padding: 2px 6px; border-radius: 4px; }
        .action-bar { display: flex; justify-content: space-between; gap: 12px; margin-bottom: 15px; flex-wrap: wrap; }
        #searchInput { flex-grow: 1; border: 1px solid #cbd5e0; border-radius: 6px; padding: 10px; min-width: 200px; }
        .btn-group { display: flex; gap: 8px; }
        .btn-success { background: #059669; color: white; border: none; padding: 10px 15px; border-radius: 6px; font-weight: 600; cursor: pointer; }
        .btn-danger { background: #e11d48; color: white; border: none; padding: 10px 15px; border-radius: 6px; font-weight: 600; cursor: pointer; }
        .btn-restore { background: #64748b; color: white; border: none; padding: 10px 15px; border-radius: 6px; font-weight: 600; cursor: pointer; }
        table { width: 100%; border-collapse: collapse; background: white; margin-top: 10px; }
        th { background: #f1f5f9; padding: 14px; text-align: left; font-size: 11px; font-weight: 700; color: #475569; text-transform: uppercase; border-bottom: 2px solid #e2e8f0; }
        td { padding: 14px; border-bottom: 1px solid #f1f5f9; font-size: 13px; }
        .id-badge { display: block; font-size: 11px; color: #94a3b8; margin-top: 3px; }
        .wa-link { color: #25D366; text-decoration: none; font-weight: 700; border: 1px solid #25D366; padding: 5px 8px; border-radius: 5px; font-size: 11px; white-space: nowrap;}
        .delete-btn { color: #94a3b8; cursor: pointer; border: none; background: none; font-size: 12px; }
        #trashSection { display: none; background: #fff1f2; padding: 15px; border-radius: 12px; margin-bottom: 20px; border: 2px dashed #fda4af; }
        @media (max-width: 600px) { .leader-card-small { bottom: 100px; left: 10px; } .floating-logo { bottom: 100px; } }
    </style>
</head>
<body>

<div id="loginOverlay">
    <div class="login-box">
        <img src="https://i.postimg.cc/9rn4BN6W/NFVT-Logo.jpg" style="width: 80px; margin-bottom: 15px; border-radius: 8px;">
        <h2 style="margin: 0 0 15px 0; font-size: 18px;">Team Followup Login</h2>
        <input type="number" id="loginId" placeholder="Distributor ID">
        <input type="password" id="loginPass" placeholder="Password">
        <button class="login-btn" onclick="checkLogin()">Login</button>
        <p id="errorMsg" style="color: red; font-size: 12px; display: none; margin-top: 10px;">ID அல்லது Password தவறு!</p>
    </div>
</div>

<div class="container" id="mainApp">
    <div class="header-section">
        <img src="https://i.postimg.cc/9rn4BN6W/NFVT-Logo.jpg" alt="NFVT Logo" class="team-logo">
        <h1>NFVT Team Followup</h1>
    </div>

    <div class="leader-card-small">
        <div class="profile-circle-small">
            <img src="https://i.postimg.cc/LhqXwQ9Y/Leader.jpg" alt="Girish S">
        </div>
        <div class="leader-info-small">
            <p class="leader-name-small">Girish S</p>
            <span class="leader-rank-small">UCD</span>
            <a href="https://www.instagram.com/girish_business/#" target="_blank" class="contact-btn-small">📲 Contact</a>
        </div>
    </div>

    <img src="https://i.postimg.cc/PNWQDG2x/New-Logo.jpg" alt="Team Branding" class="floating-logo">

    <div class="form-section">
        <div class="grid-form">
            <div class="input-group"><label>Member Name</label><input type="text" id="downlineName"></div>
            <div class="input-group"><label>Distributor ID</label><input type="number" id="distId" oninput="if(this.value.length > 8) this.value = this.value.slice(0, 8);" placeholder="8 Digit ID"></div>
            <div class="input-group">
                <label>Level</label>
                <select id="memberLevel">
                    <option value="5%">5%</option><option value="8%">8%</option><option value="12%">12%</option><option value="16%">16%</option>
                    <option value="BRONZE DIRECTOR">BRONZE DIRECTOR</option><option value="SILVER DIRECTOR">SILVER DIRECTOR</option>
                    <option value="GOLD DIRECTOR">GOLD DIRECTOR</option><option value="CROWN DIRECTOR">CROWN DIRECTOR</option>
                    <option value="UCD">UCD</option><option value="DCD">DCD</option><option value="DUCD">DUCD</option>
                </select>
            </div>
            <div class="input-group"><label>Self PV</label><input type="number" id="selfPV"></div>
            <div class="input-group"><label>Date</label><input type="date" id="followUpDate"></div>
            <div class="input-group"><label>100PV Consistency</label><select id="consistency"><option value="Yes">Yes</option><option value="No">No</option></select></div>
            <div class="input-group"><label>8% Achiever?</label><select id="achiever"><option value="No">No</option><option value="Yes">Yes</option></select></div>
            <div class="input-group"><label>Meeting Attended?</label><select id="meeting"><option value="Yes">Yes</option><option value="No">No</option></select></div>
            <button class="add-btn" onclick="addData()">Add Member</button>
        </div>
    </div>

    <div id="trashSection">
        <h3 style="font-size: 14px; margin: 0 0 10px 0; color: #be185d;">♻️ Deleted Members (Recycle Bin)</h3>
        <table style="background: transparent;">
            <tbody id="trashBody"></tbody>
        </table>
        <button onclick="toggleTrash()" style="margin-top: 10px; font-size: 11px; cursor: pointer; padding: 5px 10px;">Close Trash</button>
    </div>

    <div class="action-bar">
        <input type="text" id="searchInput" onkeyup="filterTable()" placeholder="பெயர் அல்லது ID தேடுக...">
        <div class="btn-group">
            <button class="btn-success" onclick="downloadCSV()">Excel</button>
            <button class="btn-danger" onclick="downloadPDF()">PDF</button>
            <button class="btn-restore" onclick="toggleTrash()">Restore</button>
        </div>
    </div>

    <div style="overflow-x: auto;">
        <table>
            <thead>
                <tr>
                    <th>Distributor & ID</th><th>Level</th><th>PV</th><th>Date</th><th>100PV</th><th>8%</th><th>Meeting</th><th>Action</th><th>WhatsApp</th>
                </tr>
            </thead>
            <tbody id="tableBody"></tbody>
        </table>
    </div>
</div>

<script>
    function checkLogin() {
        const id = document.getElementById('loginId').value;
        const pass = document.getElementById('loginPass').value;
        if(id.length === 8 && pass === "nfvt") {
            document.getElementById('loginOverlay').style.display = 'none';
            document.getElementById('mainApp').style.display = 'block';
            displayData();
        } else {
            document.getElementById('errorMsg').style.display = 'block';
        }
    }

    window.onload = function() { 
        document.getElementById('followUpDate').value = new Date().toISOString().split('T')[0];
    };

    function addData() {
        const name = document.getElementById('downlineName').value;
        const distId = document.getElementById('distId').value;
        const level = document.getElementById('memberLevel').value;
        const pv = parseFloat(document.getElementById('selfPV').value) || 0;
        const rawDate = document.getElementById('followUpDate').value;
        const consistency = document.getElementById('consistency').value;
        const achiever = document.getElementById('achiever').value;
        const meeting = document.getElementById('meeting').value;

        if (!name || distId.length !== 8) { 
            alert("Distributor ID சரியாக 8 இலக்க எண்களாக இருக்க வேண்டும்!"); 
            return; 
        }

        const entry = { name, distId, level, pv, rawDate, consistency, achiever, meeting, id: Date.now() };
        let entries = JSON.parse(localStorage.getItem('nfvt_ucd_final')) || [];
        entries.unshift(entry); 
        localStorage.setItem('nfvt_ucd_final', JSON.stringify(entries));

        document.getElementById('downlineName').value = '';
        document.getElementById('distId').value = '';
        document.getElementById('selfPV').value = '';
        displayData();
    }

    function displayData() {
        const tableBody = document.getElementById('tableBody');
        const entries = JSON.parse(localStorage.getItem('nfvt_ucd_final')) || [];
        tableBody.innerHTML = '';

        entries.forEach(item => {
            let rowClass = '';
            if (item.consistency === "No") rowClass = 'class="no-consistency"';
            else if (item.pv >= 100) rowClass = 'class="high-pv"';
            else if (item.achiever === 'Yes') rowClass = 'class="achiever-row"';

            const pvStyle = item.pv < 30 ? 'class="status-red"' : '';
            let message = (item.pv < 100)
                ? `வணக்கம் ${item.name}, உங்கள் தற்போதைய Level: ${item.level} மற்றும் Self PV: ${item.pv}. தயவுசெய்து 100 PV முடித்து, Consistency நன்மைகளை தவறாமல் பெற்றுக் கொள்ளவும். வாழ்த்துகள்! - Team NFVT`
                : `வாழ்த்துகள் ${item.name}! நீங்கள் ${item.level} நிலையில் 100 PV Consistency-ல் உள்ளீர்கள். உங்கள் இன்றைய PV: ${item.pv}. முன்னேற வாழ்த்துகள்! - Team NFVT`;

            const waLink = `https://wa.me/?text=${encodeURIComponent(message)}`;

            tableBody.innerHTML += `
                <tr ${rowClass}>
                    <td><strong>${item.name}</strong><span class="id-badge">ID: ${item.distId}</span></td>
                    <td><span style="font-weight:700; color:#1e293b; font-size:11px;">${item.level}</span></td>
                    <td><span ${pvStyle}>${item.pv} PV</span></td>
                    <td>${item.rawDate.split('-').reverse().join('/')}</td>
                    <td>${item.consistency}</td>
                    <td>${item.achiever}</td>
                    <td>${item.meeting}</td>
                    <td><button class="delete-btn" onclick="deleteEntry(${item.id})">Remove</button></td>
                    <td><a href="${waLink}" target="_blank" class="wa-link">📲 WhatsApp</a></td>
                </tr>`;
        });
        displayTrash();
    }

    function deleteEntry(id) {
        if(confirm("நீக்க வேண்டுமா? (இதை பிறகு Restore செய்யலாம்)")) {
            let entries = JSON.parse(localStorage.getItem('nfvt_ucd_final')) || [];
            let trash = JSON.parse(localStorage.getItem('nfvt_trash')) || [];
            const item = entries.find(e => e.id === id);
            trash.push(item);
            const remaining = entries.filter(e => e.id !== id);
            localStorage.setItem('nfvt_ucd_final', JSON.stringify(remaining));
            localStorage.setItem('nfvt_trash', JSON.stringify(trash));
            displayData();
        }
    }

    function displayTrash() {
        const trashBody = document.getElementById('trashBody');
        const trash = JSON.parse(localStorage.getItem('nfvt_trash')) || [];
        trashBody.innerHTML = '';
        if (trash.length === 0) { trashBody.innerHTML = '<tr><td>Trash is empty</td></tr>'; return; }
        trash.forEach(item => {
            trashBody.innerHTML += `
                <tr>
                    <td>${item.name} (${item.distId})</td>
                    <td><button onclick="restoreEntry(${item.id})" style="color: green; font-weight:bold; cursor:pointer; border:none; background:none;">Restore</button></td>
                    <td><button onclick="permanentDelete(${item.id})" style="color: red; cursor:pointer; border:none; background:none;">Delete</button></td>
                </tr>`;
        });
    }

    function restoreEntry(id) {
        let entries = JSON.parse(localStorage.getItem('nfvt_ucd_final')) || [];
        let trash = JSON.parse(localStorage.getItem('nfvt_trash')) || [];
        const item = trash.find(e => e.id === id);
        entries.unshift(item);
        const remainingTrash = trash.filter(e => e.id !== id);
        localStorage.setItem('nfvt_ucd_final', JSON.stringify(entries));
        localStorage.setItem('nfvt_trash', JSON.stringify(remainingTrash));
        displayData();
    }

    function permanentDelete(id) {
        if(confirm("நிரந்தரமாக நீக்க வேண்டுமா?")) {
            let trash = JSON.parse(localStorage.getItem('nfvt_trash')) || [];
            trash = trash.filter(e => e.id !== id);
            localStorage.setItem('nfvt_trash', JSON.stringify(trash));
            displayTrash();
        }
    }

    function toggleTrash() {
        const ts = document.getElementById('trashSection');
        ts.style.display = ts.style.display === 'none' ? 'block' : 'none';
    }

    function filterTable() {
        const query = document.getElementById("searchInput").value.toUpperCase();
        const rows = document.getElementById("tableBody").getElementsByTagName("tr");
        for (let row of rows) { row.style.display = row.innerText.toUpperCase().includes(query) ? "" : "none"; }
    }

    function downloadCSV() {
        const entries = JSON.parse(localStorage.getItem('nfvt_ucd_final')) || [];
        let csv = "Name,ID,Level,PV,Consistency,8Percent,Meeting\n";
        entries.forEach(e => { csv += `"${e.name}","${e.distId}","${e.level}","${e.pv}","${e.consistency}","${e.achiever}","${e.meeting}"\n`; });
        const blob = new Blob([csv], { type: 'text/csv' });
        const a = document.createElement('a'); a.href = URL.createObjectURL(blob); a.download = "NFVT_Report.csv"; a.click();
    }

    function downloadPDF() {
        const { jsPDF } = window.jspdf;
        const doc = new jsPDF();
        const entries = JSON.parse(localStorage.getItem('nfvt_ucd_final')) || [];
        doc.text("Vestige NFVT Team Report", 14, 15);
        const data = entries.map(e => [e.name, e.level, e.pv, e.consistency, e.achiever, e.meeting]);
        doc.autoTable({ head: [['Name', 'Level', 'PV', '100PV', '8%', 'Meeting']], body: data, startY: 20 });
        doc.save("Team_Report.pdf");
    }
</script>
</body>
</html>
