—-
layout: page
title: KieronPlay - Top Up Game Credits
—
<style>
/* Desktop: Two-column layout */
@media (min-width: 1024px) {
  .main-container {
    display: flex;
    gap: 2rem;
    max-width: 1400px;
    margin: 0 auto;
  }
  
  .content-column {
    flex: 1;
    min-width: 0;
  }
  
  .checker-column {
    width: 400px;
    flex-shrink: 0;
    position: sticky;
    top: 2rem;
    height: fit-content;
  }
}

/* Mobile: Stacked layout */
@media (max-width: 1023px) {
  .main-container {
    display: block;
  }
  
  .checker-column {
    margin-top: 2rem;
    max-width: 100%;
    padding: 0 1rem;
  }
  
  .id-checker-card {
    padding: 1.5rem;
  }
  
  .checker-form {
    padding: 1rem;
  }
}

/* ID Checker Styles */
.id-checker-card {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 20px;
  padding: 2rem;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);
  overflow: hidden;
}

.checker-header {
  text-align: center;
  margin-bottom: 1.5rem;
}

.checker-icon {
  width: 60px;
  height: 60px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 15px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}

.checker-header h3 {
  color: white;
  font-size: 1.5rem;
  margin: 0 0 0.5rem 0;
}

.checker-header p {
  color: rgba(255, 255, 255, 0.9);
  font-size: 0.875rem;
  margin: 0;
}

.checker-form {
  background: white;
  border-radius: 15px;
  padding: 1.5rem;
}

.form-group {
  margin-bottom: 1rem;
}

.form-group label {
  display: block;
  font-weight: 600;
  color: #333;
  margin-bottom: 0.5rem;
  font-size: 0.875rem;
}

.form-group select,
.form-group input {
  width: 100%;
  padding: 0.75rem;
  border: 2px solid #e5e7eb;
  border-radius: 10px;
  font-size: 0.875rem;
  transition: all 0.3s;
  box-sizing: border-box;
  max-width: 100%;
}

.form-group select:focus,
.form-group input:focus {
  outline: none;
  border-color: #667eea;
  box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
}

#zoneGroup {
  display: none;
}

#zoneGroup.show {
  display: block;
}

.btn-check {
  width: 100%;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border: none;
  padding: 1rem;
  border-radius: 10px;
  font-weight: 600;
  font-size: 0.875rem;
  cursor: pointer;
  transition: all 0.3s;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
}

.btn-check:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
}

.btn-check:disabled {
  opacity: 0.5;
  cursor: not-allowed;
  transform: none;
}

#resultArea {
  margin-top: 1rem;
  display: none;
}

.result-box {
  padding: 1rem;
  border-radius: 10px;
  animation: slideIn 0.3s ease-out;
}

@keyframes slideIn {
  from {
    opacity: 0;
    transform: translateY(-10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.result-box.success {
  background: #d1fae5;
  border: 2px solid #6ee7b7;
}

.result-box.error {
  background: #fee2e2;
  border: 2px solid #fca5a5;
}

.result-title {
  font-weight: 700;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.result-box.success .result-title {
  color: #065f46;
}

.result-box.error .result-title {
  color: #991b1b;
}

.result-content {
  font-size: 0.875rem;
}

.result-box.success .result-content {
  color: #047857;
}

.result-box.error .result-content {
  color: #dc2626;
}

.username-display {
  background: white;
  padding: 0.75rem;
  border-radius: 8px;
  margin-top: 0.5rem;
  border: 1px solid #6ee7b7;
}

.username-label {
  font-size: 0.75rem;
  color: #6b7280;
  margin-bottom: 0.25rem;
}

.username-value {
  font-size: 1.125rem;
  font-weight: 700;
  color: #111827;
}

.checker-info {
  background: rgba(255, 255, 255, 0.1);
  border-radius: 10px;
  padding: 0.75rem;
  margin-top: 1rem;
  text-align: center;
}

.checker-info p {
  color: rgba(255, 255, 255, 0.9);
  font-size: 0.75rem;
  margin: 0;
}
</style>

<div class="main-container">
  <!-- Main Content Column -->
  <div class="content-column">
    <section id="hero-banner">
      <div class="promo-banner">
        <h1>⚡ INSTANT GAME CREDITS TOP-UP</h1>
        <p>Fast, secure payments with PayNow (SGD). No chargebacks, instant delivery.</p>
      </div>
    </section>

<section id="games">
  <h2 class="section-title">TOP-UP GAME CREDITS</h2>
  
  <div class="game-grid">
    <div class="game-card">
      <div class="game-thumbnail mlbb-bg">
        <span class="game-logo">MLBB</span>
      </div>
      <h3>Mobile Legends</h3>
      <p class="game-subtitle">Diamonds • SGD 1-10</p>
      <a href="/select-package.html?game=mlbb" class="btn-topup">Top Up Now</a>
    </div>
    
    <div class="game-card">
      <div class="game-thumbnail wwm-bg">
        <span class="game-logo">WWM</span>
      </div>
      <h3>Where Wind Meets</h3>
      <p class="game-subtitle">Credits • SGD 1-10</p>
      <a href="/select-package.html?game=wwm" class="btn-topup">Top Up Now</a>
    </div>
    
    <div class="game-card">
      <div class="game-thumbnail mr-bg">
        <span class="game-logo">MR</span>
      </div>
      <h3>Marvel Rivals</h3>
      <p class="game-subtitle">Credits • SGD 1-10</p>
      <a href="/select-package.html?game=mr" class="btn-topup">Top Up Now</a>
    </div>
  </div>
</section>

<section id="payment-info">
  <h2 class="section-title">💳 PAYMENT METHODS</h2>
  
  <div class="payment-grid">
    <div class="payment-option active">
      <div class="payment-icon">✅</div>
      <h3>PayNow (SGD)</h3>
      <p>Instant bank transfer</p>
      <span class="status available">AVAILABLE</span>
    </div>
    
    <div class="payment-option disabled">
      <div class="payment-icon">🚧</div>
      <h3>FPX (MYR)</h3>
      <p>Malaysia online banking</p>
      <span class="status coming-soon">COMING SOON</span>
    </div>
  </div>
</section>

<section id="features-section">
  <h2 class="section-title">✨ WHY CHOOSE KIERONPLAY?</h2>
  
  <div class="features-grid">
    <div class="feature-box">
      <div class="feature-icon">⚡</div>
      <h3>Instant Delivery</h3>
      <p>Credits delivered within minutes</p>
    </div>
    
    <div class="feature-box">
      <div class="feature-icon">🔒</div>
      <h3>Secure Payment</h3>
      <p>Protected by Airwallex</p>
    </div>
    
    <div class="feature-box">
      <div class="feature-icon">💯</div>
      <h3>No Chargebacks</h3>
      <p>PayNow payments are final</p>
    </div>
    
    <div class="feature-box">
      <div class="feature-icon">📱</div>
      <h3>Mobile Friendly</h3>
      <p>Works on all devices</p>
    </div>
  </div>
</section>

<section id="contact-section">
  <h2 class="section-title">📞 SUPPORT</h2>
  <p style="text-align: center; color: #949ba4; margin-bottom: 1.5rem;">Need help? Contact us anytime.</p>
  
  <div class="contact-buttons">
    <a href="https://wa.me/65XXXXXXXX" class="contact-btn whatsapp" target="_blank">
      💬 WhatsApp
    </a>
    <a href="https://instagram.com/kieronplay" class="contact-btn instagram" target="_blank">
      📸 Instagram
    </a>
  </div>
</section>

<div class="notice-box">
  <h3>⚠️ IMPORTANT NOTICE</h3>
  <ul>
    <li><strong>Verify your details:</strong> Ensure UserID/ServerID are correct before payment</li>
    <li><strong>No refunds:</strong> No refunds for wrong account details</li>
    <li><strong>Instant delivery:</strong> Credits delivered automatically after payment</li>
  </ul>
</div>

  </div>

  <!-- ID Checker Sidebar Column -->

  <div class="checker-column">
    <div class="id-checker-card">
      <div class="checker-header">
        <div class="checker-icon">
          <svg style="width: 30px; height: 30px; fill: white;" viewBox="0 0 24 24">
            <path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" stroke="white" stroke-width="2" fill="none"/>
          </svg>
        </div>
        <h3>Verify Player ID</h3>
        <p>Check your game ID before top-up</p>
      </div>

```
  <div class="checker-form">
    <div class="form-group">
      <label for="gameSelect">Select Game</label>
      <select id="gameSelect">
        <option value="">Choose a game...</option>
        <option value="mobilelegends">Mobile Legends</option>
        <option value="freefire">Free Fire</option>
        <option value="pubgm">PUBG Mobile</option>
        <option value="genshin">Genshin Impact</option>
        <option value="codm">Call of Duty Mobile</option>
      </select>
    </div>

    <div class="form-group">
      <label for="userIdInput">Player ID</label>
      <input type="text" id="userIdInput" placeholder="Enter your player ID">
    </div>

    <div class="form-group" id="zoneGroup">
      <label for="zoneIdInput">Server ID</label>
      <input type="text" id="zoneIdInput" placeholder="Enter server ID">
    </div>

    <button id="checkBtn" class="btn-check" onclick="checkPlayerId()">
      <svg style="width: 18px; height: 18px;" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
      </svg>
      <span>Verify ID</span>
    </button>

    <div id="resultArea"></div>
  </div>

  <div class="checker-info">
    <p>✨ Demo Mode • Real API integration available</p>
  </div>
</div>

  </div>
</div>

<script>
  const gameSelect = document.getElementById('gameSelect');
  const userIdInput = document.getElementById('userIdInput');
  const zoneIdInput = document.getElementById('zoneIdInput');
  const zoneGroup = document.getElementById('zoneGroup');
  const checkBtn = document.getElementById('checkBtn');
  const resultArea = document.getElementById('resultArea');

  const gamesNeedingZone = ['mobilelegends'];
  
  const gameNames = {
    'mobilelegends': 'Mobile Legends',
    'freefire': 'Free Fire',
    'pubgm': 'PUBG Mobile',
    'genshin': 'Genshin Impact',
    'codm': 'Call of Duty Mobile'
  };

  const usernames = {
    mobilelegends: ['DragonSlayer', 'MythicKing', 'LegendPro', 'SavageMaster', 'MLBBHero'],
    freefire: ['HeadshotKing', 'BoomSquad', 'FFChampion', 'EliteGamer', 'BattleRoyal'],
    pubgm: ['ChickenDinner', 'SquadLeader', 'SniperElite', 'PUBGPro', 'WinnerWinner'],
    genshin: ['TravelerMain', 'WishMaster', 'PrimoPoor', 'GachaLuck', 'AdventureRank'],
    codm: ['CoDMobile', 'WarZonePro', 'TacticalOps', 'NukeTown', 'BlackOps']
  };

  gameSelect.addEventListener('change', (e) => {
    if (gamesNeedingZone.includes(e.target.value)) {
      zoneGroup.classList.add('show');
    } else {
      zoneGroup.classList.remove('show');
    }
  });

  async function checkPlayerId() {
    const game = gameSelect.value;
    // Sanitize inputs - remove HTML/script tags and trim
    const userId = sanitizeInput(userIdInput.value.trim());
    const zoneId = sanitizeInput(zoneIdInput.value.trim());

    if (!game || !userId) {
      showResult('error', '❌ Missing Info', 'Please select a game and enter player ID');
      return;
    }

    // Validate: only alphanumeric and basic characters
    if (!isValidInput(userId)) {
      showResult('error', '❌ Invalid Characters', 'Player ID can only contain letters, numbers, and basic punctuation');
      return;
    }

    if (userId.length < 5) {
      showResult('error', '❌ Invalid ID', 'Player ID must be at least 5 characters');
      return;
    }

    if (userId.length > 50) {
      showResult('error', '❌ ID Too Long', 'Player ID must be less than 50 characters');
      return;
    }

    checkBtn.disabled = true;
    checkBtn.innerHTML = '<span>Verifying...</span>';

    await new Promise(resolve => setTimeout(resolve, 1500));

    const randomUsername = usernames[game][Math.floor(Math.random() * usernames[game].length)] + userId.slice(-3);
    
    showResult('success', '✅ Player Found', randomUsername, {
      game: gameNames[game],
      userId: userId
    });

    checkBtn.disabled = false;
    checkBtn.innerHTML = `
      <svg style="width: 18px; height: 18px;" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
      </svg>
      <span>Verify ID</span>
    `;
  }

  // Sanitize input to prevent XSS
  function sanitizeInput(str) {
    const div = document.createElement('div');
    div.textContent = str;
    return div.innerHTML;
  }

  // Validate input format (alphanumeric, spaces, hyphens, underscores only)
  function isValidInput(str) {
    return /^[a-zA-Z0-9\s\-_]+$/.test(str);
  }

  function showResult(type, title, username, details = null) {
    let html = `<div class="result-box ${type}">`;
    // Escape HTML to prevent XSS
    const safeTitle = escapeHtml(title);
    const safeUsername = escapeHtml(username);
    
    html += `<div class="result-title">${safeTitle}</div>`;
    
    if (type === 'success' && details) {
      const safeGame = escapeHtml(details.game);
      const safeUserId = escapeHtml(details.userId);
      html += `
        <div class="username-display">
          <div class="username-label">Username</div>
          <div class="username-value">${safeUsername}</div>
        </div>
        <div class="result-content" style="margin-top: 0.5rem;">
          <strong>Game:</strong> ${safeGame}<br>
          <strong>ID:</strong> ${safeUserId}
        </div>
      `;
    } else {
      html += `<div class="result-content">${safeUsername}</div>`;
    }
    
    html += `</div>`;
    
    resultArea.innerHTML = html;
    resultArea.style.display = 'block';
  }

  // Escape HTML to prevent XSS when displaying user input
  function escapeHtml(unsafe) {
    return unsafe
      .replace(/&/g, "&amp;")
      .replace(/</g, "&lt;")
      .replace(/>/g, "&gt;")
      .replace(/"/g, "&quot;")
      .replace(/'/g, "&#039;");
  }

  userIdInput.addEventListener('keypress', (e) => {
    if (e.key === 'Enter') checkPlayerId();
  });
</script>