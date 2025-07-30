<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art Fest Live Results</title>
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
            color: white;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
            animation: fadeInDown 1s ease-out;
        }

        .header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .controls {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 10px 20px;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-size: 1rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        .btn-primary {
            background: linear-gradient(45deg, #ff6b6b, #ee5a52);
            color: white;
        }

        .btn-secondary {
            background: linear-gradient(45deg, #4ecdc4, #44a08d);
            color: white;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.3);
        }

        .admin-panel {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 30px;
            border: 1px solid rgba(255,255,255,0.2);
            display: none;
        }

        .admin-panel.active {
            display: block;
            animation: slideDown 0.5s ease-out;
        }

        .admin-form {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr auto;
            gap: 15px;
            align-items: end;
            margin-bottom: 20px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group label {
            margin-bottom: 5px;
            font-weight: bold;
        }

        .form-group input {
            padding: 10px;
            border: none;
            border-radius: 8px;
            background: rgba(255,255,255,0.9);
            color: #333;
        }

        .leaderboard {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid rgba(255,255,255,0.2);
            animation: fadeInUp 1s ease-out;
        }

        .leaderboard-header {
            background: linear-gradient(45deg, #ff6b6b, #ee5a52);
            padding: 20px;
            text-align: center;
        }

        .leaderboard-header h2 {
            font-size: 1.8rem;
            margin-bottom: 5px;
        }

        .team-list {
            padding: 0;
        }

        .team-item {
            display: grid;
            grid-template-columns: 60px 1fr auto auto;
            padding: 20px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            align-items: center;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .team-item:hover {
            background: rgba(255,255,255,0.05);
        }

        .team-item:last-child {
            border-bottom: none;
        }

        .rank {
            font-size: 1.5rem;
            font-weight: bold;
            text-align: center;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
        }

        .rank.first {
            background: linear-gradient(45deg, #ffd700, #ffed4e);
            color: #333;
        }

        .rank.second {
            background: linear-gradient(45deg, #c0c0c0, #e8e8e8);
            color: #333;
        }

        .rank.third {
            background: linear-gradient(45deg, #cd7f32, #d4a574);
            color: white;
        }

        .rank.other {
            background: rgba(255,255,255,0.2);
        }

        .team-name {
            font-size: 1.3rem;
            font-weight: bold;
            margin-left: 20px;
        }

        .points {
            font-size: 2rem;
            font-weight: bold;
            color: #4ecdc4;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }

        .points-change {
            font-size: 0.9rem;
            margin-left: 10px;
            padding: 4px 8px;
            border-radius: 12px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .points-change.positive {
            background: rgba(76, 175, 80, 0.8);
            color: white;
        }

        .points-change.negative {
            background: rgba(244, 67, 54, 0.8);
            color: white;
        }

        .points-change.show {
            opacity: 1;
        }

        .last-updated {
            text-align: center;
            margin-top: 20px;
            opacity: 0.7;
            font-size: 0.9rem;
        }

        .pulse {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes bounceIn {
            0% {
                transform: scale(0.8);
                opacity: 0;
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

        .new-team {
            animation: bounceIn 0.5s ease-out;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .admin-form {
                grid-template-columns: 1fr;
                gap: 10px;
            }
            
            .team-item {
                grid-template-columns: 50px 1fr auto;
                padding: 15px;
            }
            
            .team-name {
                font-size: 1.1rem;
                margin-left: 10px;
            }
            
            .points {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🎨 Art Fest 2025</h1>
            <p>Live Team Rankings & Results</p>
        </div>

        <div class="controls">
            <button class="btn btn-primary" onclick="toggleAdmin()">Admin Panel</button>
            <button class="btn btn-secondary" onclick="exportData()">Export Results</button>
            <button class="btn btn-secondary" onclick="resetAll()">Reset All</button>
        </div>

        <div class="admin-panel" id="adminPanel">
            <h3>🔧 Admin Controls</h3>
            <div class="admin-form">
                <div class="form-group">
                    <label>Team Name</label>
                    <input type="text" id="teamName" placeholder="Enter team name">
                </div>
                <div class="form-group">
                    <label>Points</label>
                    <input type="number" id="points" placeholder="Points">
                </div>
                <div class="form-group">
                    <label>Action</label>
                    <select id="action" style="padding: 10px; border: none; border-radius: 8px; background: rgba(255,255,255,0.9); color: #333;">
                        <option value="add">Add Points</option>
                        <option value="set">Set Total</option>
                        <option value="subtract">Subtract</option>
                    </select>
                </div>
                <button class="btn btn-primary" onclick="updateTeam()">Update</button>
            </div>
        </div>

        <div class="leaderboard">
            <div class="leaderboard-header">
                <h2>🏆 Live Leaderboard</h2>
                <p>Real-time team standings</p>
            </div>
            <div class="team-list" id="teamList">
                <!-- Teams will be populated here -->
            </div>
            <div class="last-updated" id="lastUpdated">
                Last updated: Never
            </div>
        </div>
    </div>

    <script>
        let teams = [
            { name: "Team A", points: 0 },
            { name: "Team B", points: 0 },
            { name: "Team C", points: 0 },
            { name: "Team D", points: 0 }
        ];

        let adminVisible = false;

        function toggleAdmin() {
            const panel = document.getElementById('adminPanel');
            adminVisible = !adminVisible;
            panel.classList.toggle('active', adminVisible);
        }

        function updateTeam() {
            const teamName = document.getElementById('teamName').value.trim();
            const points = parseInt(document.getElementById('points').value) || 0;
            const action = document.getElementById('action').value;

            if (!teamName) {
                alert('Please enter a team name');
                return;
            }

            let team = teams.find(t => t.name.toLowerCase() === teamName.toLowerCase());
            let isNewTeam = false;

            if (!team) {
                team = { name: teamName, points: 0 };
                teams.push(team);
                isNewTeam = true;
            }

            const oldPoints = team.points;

            switch(action) {
                case 'add':
                    team.points += points;
                    break;
                case 'set':
                    team.points = points;
                    break;
                case 'subtract':
                    team.points = Math.max(0, team.points - points);
                    break;
            }

            // Clear form
            document.getElementById('teamName').value = '';
            document.getElementById('points').value = '';

            renderLeaderboard(isNewTeam ? team.name : null, oldPoints !== team.points ? team.points - oldPoints : null);
        }

        function renderLeaderboard(newTeamName = null, pointsChange = null) {
            // Sort teams by points
            teams.sort((a, b) => b.points - a.points);

            const teamList = document.getElementById('teamList');
            teamList.innerHTML = '';

            teams.forEach((team, index) => {
                const teamItem = document.createElement('div');
                teamItem.className = 'team-item';
                if (newTeamName === team.name) {
                    teamItem.classList.add('new-team');
                }

                const rank = index + 1;
                let rankClass = 'other';
                if (rank === 1) rankClass = 'first';
                else if (rank === 2) rankClass = 'second';
                else if (rank === 3) rankClass = 'third';

                let changeIndicator = '';
                if (pointsChange !== null && newTeamName === team.name) {
                    const changeClass = pointsChange > 0 ? 'positive' : pointsChange < 0 ? 'negative' : '';
                    const changeSymbol = pointsChange > 0 ? '+' : '';
                    changeIndicator = `<span class="points-change ${changeClass} show">${changeSymbol}${pointsChange}</span>`;
                }

                teamItem.innerHTML = `
                    <div class="rank ${rankClass}">${rank}</div>
                    <div class="team-name">${team.name}</div>
                    <div class="points ${pointsChange !== null && newTeamName === team.name ? 'pulse' : ''}">${team.points}</div>
                    <div>${changeIndicator}</div>
                `;

                teamList.appendChild(teamItem);
            });

            // Update timestamp
            const now = new Date();
            document.getElementById('lastUpdated').textContent = 
                `Last updated: ${now.toLocaleTimeString()}`;

            // Hide change indicators after 3 seconds
            setTimeout(() => {
                document.querySelectorAll('.points-change').forEach(el => {
                    el.classList.remove('show');
                });
            }, 3000);
        }

        function exportData() {
            const data = {
                timestamp: new Date().toISOString(),
                teams: teams
            };
            
            const blob = new Blob([JSON.stringify(data, null, 2)], { type: 'application/json' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `art_fest_results_${new Date().toISOString().split('T')[0]}.json`;
            a.click();
            URL.revokeObjectURL(url);
        }

        function resetAll() {
            if (confirm('Are you sure you want to reset all team points to zero?')) {
                teams.forEach(team => team.points = 0);
                renderLeaderboard();
            }
        }

        // Initialize the leaderboard
        renderLeaderboard();

        // Auto-refresh every 30 seconds (optional)
        setInterval(() => {
            renderLeaderboard();
        }, 30000);
    </script>
</body>
</html>
