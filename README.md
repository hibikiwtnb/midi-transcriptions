# midi-transcriptions

由 AI 輔助生成的 MIDI 轉錄，並由人工進行修正與改進。

AI-assisted MIDI transcriptions, corrected and improved by human contributors.

## 技術介紹

本倉庫中的 MIDI 主要由 **MuScriptor Large** 模型生成。

由於模型生成的 MIDI 會固定為 **120 BPM**，我會使用 [hibikiwtnb/pianotrans-tools](https://github.com/hibikiwtnb/pianotrans-tools) 對 BPM 進行修正。修正後的 MIDI 檔名會帶有 `_bpmfix` 標記，例如：[bpmfix](https://github.com/hibikiwtnb/midi-transcriptions/blob/main/midi/CYaRon-%E5%85%83%E6%B0%97%E5%85%A8%E9%96%8BDAY%20DAY%20DAY%20Off%20Vocal_bpmfix.mid "CYaRon-元気全開DAY DAY DAY Off Vocal_bpmfix.mid")。

## Technical notes

The MIDI files in this repository are primarily generated with the **MuScriptor Large** model.

Because the model outputs MIDI files at a fixed **120 BPM**, I use [hibikiwtnb/pianotrans-tools](https://github.com/hibikiwtnb/pianotrans-tools) to correct the BPM. Corrected MIDI files are marked with `_bpmfix` in the filename, for example: [bpmfix](https://github.com/hibikiwtnb/midi-transcriptions/blob/main/midi/CYaRon-%E5%85%83%E6%B0%97%E5%85%A8%E9%96%8BDAY%20DAY%20DAY%20Off%20Vocal_bpmfix.mid "CYaRon-元気全開DAY DAY DAY Off Vocal_bpmfix.mid").

## 分享與授權

這些 MIDI 檔案旨在供學習、修正、修改與分享使用。

原始音樂作品的著作權仍屬於各自的權利人。本倉庫不主張擁有這些原始作品的著作權，也不授予貢獻者本身無權授予的任何權利。

在本倉庫貢獻者對 MIDI 轉錄、修正、編輯、編曲或其他原創貢獻依法享有著作權或其他適用權利的範圍內，這些貢獻均以 **Creative Commons 姓名標示－相同方式分享 4.0 國際（CC BY-SA 4.0）** 授權。

你**不需要公開自己的修改**，也不需要將修改提交回本倉庫。但是，如果你將修改或改進後的 MIDI 分享給其他人，則必須讓其中適用的貢獻內容繼續以 CC BY-SA 4.0 或相容的「相同方式分享」授權提供。

本倉庫不代表相關 MIDI 已取得商業利用所需的全部授權。任何將這些 MIDI 用於商業用途的人，都有責任自行取得原始音樂作品及其他第三方權利所需的許可。

詳細條款請參閱 [`LICENSE`](LICENSE)。

## Sharing and license

These MIDI files are intended for study, correction, modification, and sharing.

Copyright in the underlying musical compositions remains with the respective copyright holders. This repository does not claim ownership of those compositions or grant rights that its contributors do not have.

To the extent that copyright or other applicable rights exist in the transcriptions, corrections, edits, arrangements, or other original contributions made by contributors to this repository, those contributions are licensed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.

You are **not required to publish your modifications** or submit them back to this repository. However, if you share a modified or improved MIDI with others, you must keep the applicable contributions available under CC BY-SA 4.0 or a compatible ShareAlike license.

Commercial use is not automatically cleared by this repository. Anyone using these MIDI files commercially is responsible for obtaining any permissions required for the underlying musical composition and other third-party rights.

See [`LICENSE`](LICENSE) for details.
