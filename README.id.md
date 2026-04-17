<div align="center">

# Oh My Indo

### Fork bertema Indonesia dari [oh-my-opencode](https://github.com/code-yeongyu/oh-my-openagent)

Semua agent diganti nama jadi tokoh sejarah dan pahlawan nasional Indonesia. Merdeka!

[English](README.md) | [Bahasa Indonesia](README.id.md)

</div>

---

## Apa ini?

**Oh My Indo** adalah fork dari [oh-my-opencode](https://github.com/code-yeongyu/oh-my-openagent) (oleh [@code-yeongyu](https://github.com/code-yeongyu)) dengan satu modifikasi utama:

**Semua agent diganti nama** jadi tokoh sejarah/pahlawan nasional Indonesia — dari proklamator sampai ksatria legendaris Nusantara.

### Daftar Agent

| Asli | Oh My Indo | Peran |
|------|------------|-------|
| Sisyphus | **Soekarno** | Orkestrator utama. Proklamator. Memimpin kode seperti memimpin bangsa. |
| Hephaestus | **Gajah Mada** | Deep worker otonom. Mahapatih legendaris Majapahit yang menyatukan Nusantara. |
| Oracle | **Ki Hajar Dewantara** | Konsultan read-only. Bapak Pendidikan Indonesia. Kebijaksanaan tanpa aksi. |
| Librarian | **Kartini** | Pencari dokumentasi. Pelopor pengetahuan dan literasi untuk semua. |
| Explore | **Hang Tuah** | Pencari codebase. Sang Laksamana legendaris menjelajahi setiap sudut Nusantara. |
| Atlas | **Soeharto** | Orkestrator todo. Sang Pengorganisir Agung Orde Baru. |
| Prometheus | **Sultan HB IX** | Perencana strategis. Sultan bijaksana yang merancang strategi kemerdekaan Indonesia. |
| Metis | **Diponegoro** | Konsultan pra-perencanaan. Pangeran Perang Jawa. Ahli strategi ulung. |
| Momus | **Pramoedya** | Reviewer/kritikus plan. Suara sastra dan kritikus sosial terbesar Indonesia. |
| Sisyphus-Junior | **Pemuda** | Eksekutor tugas. Gerakan pemuda. Menjalankan perintah dengan semangat revolusioner. |
| Multimodal Looker | **Majapahit** | Analisis vision/PDF. Kerajaan besar yang menjelajahi dan memetakan Nusantara. |

### Kenapa Tokoh Indonesia?

Karena kode kamu layak diorkestrasi oleh pemimpin sekaliber mereka yang membangun bangsa dari 17.000 pulau. Ketika Soekarno mengorkestrasi agent-mu, Gajah Mada menyelam dalam ke implementasi, dan Kartini mencari dokumentasi — kamu tahu kode-mu ada di tangan yang tepat.

---

## Instalasi

### Dari npm

```bash
bun add -g oh-my-indo
```

Atau pakai npm:

```bash
npm install -g oh-my-indo
```

### Konfigurasi OpenCode

Edit `~/.config/opencode/opencode.json` (atau `opencode.jsonc`):

```json
{
  "plugin": ["oh-my-indo"]
}
```

### Verifikasi

```bash
opencode
# Ketik "ultrawork" untuk mengaktifkan semua agent
```

---

## Install dari source

```bash
git clone https://github.com/nsulistiyawan/oh-my-indo.git
cd oh-my-indo
bun install
bun run build
bun link
```

Lalu tambahkan `"oh-my-indo"` ke array plugin di `opencode.json`.

---

## Fitur dari Upstream

Fork ini mewarisi semua fitur dari oh-my-opencode:

| Fitur | Deskripsi |
|-------|-----------|
| **Discipline Agents** | Soekarno mengorkestrasi Gajah Mada, Ki Hajar Dewantara, Kartini, Hang Tuah secara paralel |
| **`ultrawork` / `ulw`** | Satu kata mengaktifkan semua agent. Jalan terus sampai selesai |
| **IntentGate** | Menganalisis intent asli user sebelum bertindak |
| **Hash-Anchored Edits** | Hash konten `LINE#ID` memvalidasi setiap perubahan |
| **LSP + AST-Grep** | Refactoring presisi IDE untuk agent |
| **Background Agents** | 5+ spesialis berjalan paralel |
| **Built-in MCPs** | Exa (web search), Context7 (docs), Grep.app (GitHub search) |
| **Ralph Loop** | Loop self-referential sampai 100% selesai |
| **Sultan HB IX Planner** | Perencanaan strategis mode interview sebelum eksekusi |
| **Kompatibel Claude Code** | Semua hooks, commands, skills, MCPs tetap berfungsi |

Untuk dokumentasi lengkap, lihat [project upstream](https://github.com/code-yeongyu/oh-my-openagent).

---

## Lisensi

[SUL-1.0](LICENSE.md)
