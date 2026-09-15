# The Aeneid — Virgil  ·  _classics_

> Bu kitabın **hub klasörü**. Kitaba dair her şey (config, meta, prompt, upload pack) burada; render çıktıları `public/` ve `out/` altında, aşağıda linkli.

## Dosyalar

| | Konum | Not |
|---|---|---|
| 🎬 Final video | `out/the-aeneid.mp4` _(yok)_ | render çıktısı |
| 🖼️ Thumbnail | [`out/thumbnail-the-aeneid.png`](../../out/thumbnail-the-aeneid.png) | YouTube kapak |
| 📝 YouTube pack | [`books/the-aeneid/youtube.md`](youtube.md) | başlık/açıklama/tag/bölümler |
| 💬 Captions (CC) | [`public/captions/the-aeneid.clean.vtt`](../../public/captions/the-aeneid.clean.vtt) | YouTube'a "With timing" yükle |
| 💬 Captions (ham) | [`public/captions/the-aeneid.vtt`](../../public/captions/the-aeneid.vtt) | kelime-zamanlı (karaoke kaynağı) |
| 🎙️ Audio | [`public/audio/the-aeneid.m4a`](../../public/audio/the-aeneid.m4a) | NotebookLM sesi |
| 🖼️ Scene images | [`public/scenes/the-aeneid/`](../../public/scenes/the-aeneid) | Flux görselleri |
| ✍️ NotebookLM prompt | [`books/the-aeneid/prompt.notebooklm.md`](prompt.notebooklm.md) | orijinal analiz açısı |
| 📖 Manifest | [`books/the-aeneid/book.json`](book.json) | book.json (slug/başlık/engine) |
| ⚙️ Vox config | [`books/the-aeneid/config.vox.json`](config.vox.json) | render config (beats/captions) |
| ⚙️ YouTube meta | [`books/the-aeneid/youtube-meta.json`](youtube-meta.json) | SEO/meta + thumbnail brief |
| 🎞️ Render chunks | `out_Vox-the-aeneid_chunks/` _(yok)_ | ara mp4 parçaları + parts.txt |

## Yükleme sırası
1. `out/the-aeneid.mp4` yükle
2. Başlık + açıklama (bölümler tıklanabilir olur) + tag → [youtube.md](youtube.md)
3. Thumbnail → `out/thumbnail-the-aeneid.png`
4. CC → `the-aeneid.clean.vtt` ("With timing")
5. **Altered content = Yes** (sentetik ses)

## Yeniden üretmek
```bash
node scripts/make-book.js --slug=the-aeneid --title="The Aeneid" --author="Virgil" --genre=classics
```
