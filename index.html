<!DOCTYPE html>
<html lang="id" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Affiliate Copywriter Studio — Threads & IG</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Plus Jakarta Sans', sans-serif; }
    .loader {
      border: 3px solid rgba(255, 255, 255, 0.15);
      border-top-color: #10b981;
      border-radius: 50%;
      width: 22px;
      height: 22px;
      animation: spin 0.8s linear infinite;
    }
    @keyframes spin { to { transform: rotate(360deg); } }
  </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen antialiased selection:bg-emerald-500 selection:text-white">

  <!-- Header -->
  <header class="border-b border-slate-800/80 bg-slate-900/60 backdrop-blur-md sticky top-0 z-20">
    <div class="max-w-3xl mx-auto px-4 py-4 flex items-center justify-between">
      <div class="flex items-center gap-2.5">
        <div class="w-9 h-9 rounded-xl bg-gradient-to-br from-emerald-500 to-teal-600 flex items-center justify-center font-bold text-slate-950 shadow-lg shadow-emerald-500/20">
          ✍️
        </div>
        <div>
          <h1 class="font-bold text-base sm:text-lg tracking-tight text-white leading-tight">Affiliate Copy Studio</h1>
          <p class="text-xs text-slate-400">Generator Threads & IG Siap Copas</p>
        </div>
      </div>
      <button onclick="toggleConfig()" class="text-xs bg-slate-800 hover:bg-slate-700 text-slate-300 px-3 py-2 rounded-lg border border-slate-700 transition flex items-center gap-1.5">
        <span>⚙️</span> <span class="hidden sm:inline">API Endpoint</span>
      </button>
    </div>
  </header>

  <main class="max-w-3xl mx-auto px-4 py-6 space-y-6">

    <!-- Panel Pengaturan URL Web App GAS -->
    <div id="configPanel" class="hidden bg-slate-900 border border-amber-500/40 rounded-2xl p-4 shadow-xl space-y-3">
      <div class="flex items-center justify-between">
        <h2 class="text-sm font-semibold text-amber-400">Konfigurasi Google Apps Script URL</h2>
        <button onclick="toggleConfig()" class="text-slate-400 hover:text-white text-sm">✕</button>
      </div>
      <p class="text-xs text-slate-400">Tempel Web App URL hasil deploy <code>Code.gs</code> Anda di bawah ini. Tersimpan otomatis di browser perangkat Anda.</p>
      <div class="flex flex-col sm:flex-row gap-2">
        <input type="url" id="gasUrlInput" placeholder="https://script.google.com/macros/s/.../exec"
          class="flex-1 bg-slate-950 border border-slate-700 rounded-xl px-3.5 py-2.5 text-sm text-white focus:outline-none focus:border-emerald-500" />
        <button onclick="saveGasUrl()" class="bg-emerald-600 hover:bg-emerald-500 text-white font-semibold text-sm px-4 py-2.5 rounded-xl transition">
          Simpan URL
        </button>
      </div>
    </div>

    <!-- Form Input Utama -->
    <section class="bg-slate-900/90 border border-slate-800 rounded-2xl p-5 sm:p-6 shadow-xl space-y-4">
      <div>
        <label class="block text-xs font-semibold uppercase tracking-wider text-slate-400 mb-1.5">
          1. Link Produk Afiliasi
        </label>
        <div class="flex gap-2">
          <input type="url" id="productLink" placeholder="Tempel link Shopee / Tokopedia / TikTok Shop..."
            class="flex-1 bg-slate-950 border border-slate-700/90 rounded-xl px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-emerald-500 transition" />
          <button type="button" onclick="pasteFromClipboard('productLink')" title="Tempel dari Clipboard"
            class="bg-slate-800 hover:bg-slate-700 border border-slate-700 px-3.5 rounded-xl text-xs font-medium text-slate-300 transition">
            Paste
          </button>
        </div>
      </div>

      <div>
        <div class="flex items-center justify-between mb-1.5">
          <label class="block text-xs font-semibold uppercase tracking-wider text-slate-400">
            2. Info / Deskripsi Produk <span class="text-slate-500 font-normal normal-case">(Opsional, sangat disarankan jika link pendek)</span>
          </label>
          <button type="button" onclick="pasteFromClipboard('productDesc')" class="text-xs text-emerald-400 hover:underline">
            + Paste Teks
          </button>
        </div>
        <textarea id="productDesc" rows="3"
          placeholder="Copas judul produk, keunggulan, atau ulasan pembeli dari marketplace di sini agar AI bisa meracik angle jualan yang tajam..."
          class="w-full bg-slate-950 border border-slate-700/90 rounded-xl px-4 py-3 text-sm text-white placeholder-slate-500 focus:outline-none focus:border-emerald-500 transition"></textarea>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-1">
        <div>
          <label class="block text-xs font-semibold uppercase tracking-wider text-slate-400 mb-1.5">
            Fokus Gaya / Platform
          </label>
          <select id="platformSelect"
            class="w-full bg-slate-950 border border-slate-700/90 rounded-xl px-3.5 py-3 text-sm text-white focus:outline-none focus:border-emerald-500">
            <option value="Semua (Threads & Instagram)">Semua Paket (2 Threads + 1 IG)</option>
            <option value="Threads Storytelling & Soft-Selling">Fokus Threads (Utas & Balasan)</option>
            <option value="Instagram Caption & Carousel">Fokus Instagram (Caption Konversi)</option>
          </select>
        </div>

        <div class="flex items-end">
          <button id="generateBtn" onclick="generateCopy()"
            class="w-full bg-gradient-to-r from-emerald-500 to-teal-600 hover:from-emerald-400 hover:to-teal-500 text-slate-950 font-bold text-sm py-3 px-5 rounded-xl shadow-lg shadow-emerald-500/20 transition flex items-center justify-center gap-2">
            <span id="btnText">✨ Buat Copywriting Sekarang</span>
            <div id="btnLoader" class="loader hidden"></div>
          </button>
        </div>
      </div>
    </section>

    <!-- Info Ekstraksi URL (Jika berhasil membaca judul dari link) -->
    <div id="extractedBadge" class="hidden bg-emerald-950/50 border border-emerald-500/30 rounded-xl px-4 py-3 text-xs text-emerald-300 flex items-start gap-2">
      <span>🔍</span>
      <span id="extractedText"></span>
    </div>

    <!-- Alert Error -->
    <div id="errorBox" class="hidden bg-rose-950/60 border border-rose-500/40 rounded-xl px-4 py-3 text-sm text-rose-200"></div>

    <!-- Hasil Output Kartu Copywriting -->
    <section id="resultsContainer" class="space-y-4 hidden">
      <div class="flex items-center justify-between">
        <h2 class="text-sm font-bold uppercase tracking-wider text-slate-300">Hasil Copywriting Siap Posting</h2>
        <button onclick="clearForm()" class="text-xs text-slate-400 hover:text-white">Reset Form</button>
      </div>
      <div id="cardsWrapper" class="space-y-4"></div>
    </section>

  </main>

  <script>
    // Ganti default ini jika ingin hardcoded, atau isi lewat tombol Pengaturan di web
    const DEFAULT_GAS_URL = ""; 

    document.addEventListener("DOMContentLoaded", () => {
      const savedUrl = localStorage.getItem("affiliate_gas_url") || DEFAULT_GAS_URL;
      if (savedUrl) {
        document.getElementById("gasUrlInput").value = savedUrl;
      } else {
        document.getElementById("configPanel").classList.remove("hidden");
      }
    });

    function toggleConfig() {
      document.getElementById("configPanel").classList.toggle("hidden");
    }

    function saveGasUrl() {
      const url = document.getElementById("gasUrlInput").value.trim();
      if (!url.startsWith("https://script.google.com/")) {
        alert("Pastikan URL berawalan https://script.google.com/...");
        return;
      }
      localStorage.setItem("affiliate_gas_url", url);
      document.getElementById("configPanel").classList.add("hidden");
      showToast("URL Endpoint berhasil disimpan!");
    }

    async function pasteFromClipboard(targetId) {
      try {
        const text = await navigator.clipboard.readText();
        document.getElementById(targetId).value = text;
      } catch (err) {
        alert("Browser memblokir akses clipboard otomatis. Silakan tempel manual (Ctrl+V / Tekan & Tempel).");
      }
    }

    async function generateCopy() {
      const gasUrl = (localStorage.getItem("affiliate_gas_url") || DEFAULT_GAS_URL).trim();
      const link = document.getElementById("productLink").value.trim();
      const description = document.getElementById("productDesc").value.trim();
      const platform = document.getElementById("platformSelect").value;

      const errorBox = document.getElementById("errorBox");
      const resultsContainer = document.getElementById("resultsContainer");
      const extractedBadge = document.getElementById("extractedBadge");

      errorBox.classList.add("hidden");
      extractedBadge.classList.add("hidden");

      if (!gasUrl) {
        document.getElementById("configPanel").classList.remove("hidden");
        showError("Silakan masukkan Web App URL Google Apps Script terlebih dahulu di panel atas.");
        return;
      }

      if (!link && !description) {
        showError("Masukkan minimal Link Produk atau Info Produk terlebih dahulu.");
        return;
      }

      setLoading(true);

      try {
        // Gunakan text/plain agar terhindar dari preflight CORS OPTIONS di Google Apps Script
        const response = await fetch(gasUrl, {
          method: "POST",
          headers: { "Content-Type": "text/plain;charset=utf-8" },
          body: JSON.stringify({ link, description, platform })
        });

        const result = await response.json();

        if (result.status !== "success") {
          throw new Error(result.message || "Gagal memproses permintaan.");
        }

        if (result.extracted_hint) {
          document.getElementById("extractedText").textContent = "Terdeteksi otomatis: " + result.extracted_hint;
          extractedBadge.classList.remove("hidden");
        }

        renderCopyCards(result.data);
        resultsContainer.classList.remove("hidden");
        resultsContainer.scrollIntoView({ behavior: "smooth", block: "start" });

      } catch (err) {
        showError(err.message);
      } finally {
        setLoading(false);
      }
    }

    function renderCopyCards(rawText) {
      const wrapper = document.getElementById("cardsWrapper");
      wrapper.innerHTML = "";

      // Pecah berdasarkan delimiter ===OPSI ...=== dari Code.gs
      const sections = rawText.split(/===(.*?)===/g).filter(s => s.trim() !== "");

      if (sections.length >= 2) {
        for (let i = 0; i < sections.length; i += 2) {
          const title = sections[i].trim();
          const content = (sections[i + 1] || "").trim();
          if (content) {
            wrapper.appendChild(createCardElement(title, content, i));
          }
        }
      } else {
        // Fallback jika format AI tidak terpecah
        wrapper.appendChild(createCardElement("HASIL COPYWRITING", rawText.trim(), 0));
      }
    }

    function createCardElement(title, content, index) {
      const card = document.createElement("div");
      card.className = "bg-slate-900 border border-slate-800 rounded-2xl p-5 shadow-lg space-y-3";

      const isThreads = title.toLowerCase().includes("threads");
      const badgeColor = isThreads
        ? "bg-purple-500/15 text-purple-300 border-purple-500/30"
        : "bg-pink-500/15 text-pink-300 border-pink-500/30";

      const textareaId = `copy-content-${index}`;

      card.innerHTML = `
        <div class="flex items-center justify-between gap-2">
          <span class="text-xs font-bold px-2.5 py-1 rounded-lg border ${badgeColor}">
            ${escapeHtml(title)}
          </span>
          <button onclick="copyCardText('${textareaId}', this)"
            class="bg-slate-800 hover:bg-emerald-600 text-slate-200 hover:text-white text-xs font-semibold px-3.5 py-1.5 rounded-lg border border-slate-700 hover:border-emerald-500 transition flex items-center gap-1.5">
            <span>📋</span> <span>Copy Text</span>
          </button>
        </div>
        <textarea id="${textareaId}" rows="7"
          class="w-full bg-slate-950/90 border border-slate-800 rounded-xl p-3.5 text-sm text-slate-200 leading-relaxed focus:outline-none focus:border-emerald-500/60 resize-y">${escapeHtml(content)}</textarea>
      `;
      return card;
    }

    function copyCardText(elementId, btnElement) {
      const textarea = document.getElementById(elementId);
      textarea.select();
      textarea.setSelectionRange(0, 99999);
      navigator.clipboard.writeText(textarea.value);

      const originalHtml = btnElement.innerHTML;
      btnElement.innerHTML = `<span>✅</span> <span>Tersalin!</span>`;
      btnElement.classList.add("bg-emerald-600", "text-white", "border-emerald-500");

      setTimeout(() => {
        btnElement.innerHTML = originalHtml;
        btnElement.classList.remove("bg-emerald-600", "text-white", "border-emerald-500");
      }, 2000);
    }

    function setLoading(isLoading) {
      const btn = document.getElementById("generateBtn");
      const btnText = document.getElementById("btnText");
      const btnLoader = document.getElementById("btnLoader");

      btn.disabled = isLoading;
      if (isLoading) {
        btnText.textContent = "Meracik Copywriting...";
        btnLoader.classList.remove("hidden");
        btn.classList.add("opacity-80", "cursor-not-allowed");
      } else {
        btnText.textContent = "✨ Buat Copywriting Sekarang";
        btnLoader.classList.add("hidden");
        btn.classList.remove("opacity-80", "cursor-not-allowed");
      }
    }

    function showError(msg) {
      const box = document.getElementById("errorBox");
      box.textContent = "⚠️ " + msg;
      box.classList.remove("hidden");
    }

    function clearForm() {
      document.getElementById("productLink").value = "";
      document.getElementById("productDesc").value = "";
      document.getElementById("resultsContainer").classList.add("hidden");
      document.getElementById("extractedBadge").classList.add("hidden");
    }

    function escapeHtml(text) {
      const div = document.createElement("div");
      div.textContent = text;
      return div.innerHTML;
    }

    function showToast(msg) {
      alert(msg);
    }
  </script>
</body>
</html>
