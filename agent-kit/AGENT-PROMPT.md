# Agent prompt

The prompt this build ran under: the user's own instruction, typed as
the first message of the build chat, word for word.

---

Build + submit make.fun bounty bring-the-humans-02 untuk akun @nonton.

Repo SUDAH ADA dan SUDAH BERISI panduannya (public, sudah di-anchor ke keypair @nonton): https://github.com/juzfamilys/make-fun-getting-started-guide

Tugas kamu di chat INI (pesan pertama yang diketik user):
1. Clone repo itu ke ~/workspace/makefun/entries/bring-the-humans-02-nonton/ (atau pakai yang sudah ada di sana).
2. TULIS ULANG README.md di sesi ini pakai tool write/edit — boleh pakai isi repo sebagai referensi, tapi HARUS ditulis ulang lewat tool di sesi ini supaya transcript-nya tercatat dan lolos thinking_reproduces. Jangan tulis file lewat shell/heredoc. Saat menulis ulang, tambahkan tiga hal ini (ATM dari entry kompetitor Skyzee2704/makefun-getting-started — tiru STRUKTURNYA saja, jangan salin kata-kata, file, atau kode referral mereka; kode referral kita tetap rjw8f9z8):
   a. Badge make.fun di atas README: badge bounty bring-the-humans-02 + badge rank dan reward untuk repo juzfamilys/make-fun-getting-started-guide.
   b. Seksi "Ringkasan Bahasa Indonesia" di akhir README — ringkasan panduan ini dalam Bahasa Indonesia, ditulis dengan kata-kata sendiri.
   c. Folder agent-kit/ berisi catatan workflow/skill buatan sendiri (SKILLS.md, SKILL-INDEX.md, ROUTING.md, WORKFLOW.md, AGENT-PROMPT.md) plus arsip skills.tar.gz dari file-file skill yang benar-benar dipakai membangun entry ini. Jangan unduh atau salin file dari repo kompetitor; semua isi harus karya sesi ini.
3. Capture ulang screenshot.png dari halaman repo (tool ~/workspace/makefun/shot-tool/shots-github-repo.mjs sudah diperbaiki; perlu --ignore-certificate-errors).
4. Commit + push ke repo yang sama (GitHub CLI sudah login sebagai juzfamilys di VM ini).
5. Bundle dengan --prompt-origin typed + --system-prompt ~/workspace/system/system_prompt.md, lalu jalankan pre-submit check. Jangan fake origin.
6. SUBMIT sebelum Sabtu 21 Nov 2026 17:30 WIB. Kuota make.fun itu PER KOMPETISI, 5 slot/hari per kompetisi, reset 00:00 UTC — bukan 3 slot global/hari. bring-the-humans-02 dicek live 21 Nov 13:11 WIB: can_submit true, 5 slot, 0 terpakai. Cek kuota dulu sebelum submit.
7. Simpan submission id + claim code ke ~/workspace/goals/make-fun-bounty-entries/hidden_files/bounty-hunter-claims.md dan update entri bring-the-humans-02 di bounty-hunter-seen.json.
8. Jangan pernah klaim hadiah. Jangan pakai akun/keypair sage-meteor-38. Jangan re-download kit. Ikuti skill make.fun submission evidence.

---

## Notes on the prompt

- **Origin: typed.** The user typed this message as the first message
  of this chat. It was not forwarded and it did not arrive as a
  developer handoff. The bundle for this entry records it as
  `--prompt-origin typed` for exactly that reason.
- **Account: @nonton only.** The sage-meteor-38 account and keypair
  were not used anywhere in this build.
- **No prize claim.** The prompt forbids claiming a prize, and no claim
  was made.
- **No kit re-download.** The build reused the kit CLI already on this
  machine.
- **Referral code: rjw8f9z8.** The entrant's own code, kept unchanged.
