const games = [
  ["🎲", "منچز", "ورود به بازی"],
  ["🟪", "مارکرفت", "ورود به بازی"],
  ["🎲", "تخت نرد (پلاتو)", "ورود به بازی"],
  ["🃏", "حکم (سوبرا)", "ورود به بازی"]
];

function toast(msg) {
  const el = document.getElementById("toast");
  el.textContent = msg;
  el.classList.add("show");

  clearTimeout(window.__toast);
  window.__toast = setTimeout(
    () => el.classList.remove("show"),
    1700
  );
}

function openPanel(type) {
  const overlay = document.getElementById("overlay");
  const title = document.getElementById("sheet-title");
  const content = document.getElementById("sheet-content");

  if (type === "games") {
    title.textContent = "بازی‌ها";

    content.innerHTML = `
      <div class="games">
        ${games.map((g, i) => `
          <button class="game" onclick="gameClick(${i})">
            <div class="gicon">${g[0]}</div>
            <strong>${g[1]}</strong>
            <small>${g[2]}</small>
          </button>
        `).join("")}
      </div>
    `;

  } else if (type === "security") {
    title.textContent = "امنیت";

    content.innerHTML = `
      <div class="info">
        امنیت حساب و ورود سریع در این بخش قرار می‌گیرد.<br>
        اثر انگشت دستگاه بعد از اتصال Mini App
        به محیط امن Telegram فعال می‌شود.
      </div>
    `;

  } else {
    title.textContent = "حساب";

    content.innerHTML = `
      <div class="info">
        پروفایل، تنظیمات و اطلاعات حساب در این بخش قرار می‌گیرد.
      </div>
    `;
  }

  overlay.classList.add("show");
}

function closePanel(e) {
  if (!e || e.target.id === "overlay") {
    document.getElementById("overlay").classList.remove("show");
  }
}

function gameClick(i) {
  toast(
    "ورود به " +
    games[i][1] +
    " — لینک بازی هنوز تنظیم نشده"
  );
}

function setActive(el) {
  document
    .querySelectorAll(".nav-item")
    .forEach(x => x.classList.remove("active"));

  el.classList.add("active");
}
