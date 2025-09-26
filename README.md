# ai-terms
Bảng thuật ngữ AI có phát âm
<!doctype html>
<html lang="vi">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Thuật ngữ AI — Bảng phát âm</title>
<style>
  body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; padding: 20px; background:#f7f7f8; color:#111; }
  table { border-collapse: collapse; width: 100%; max-width: 1000px; margin: 0 auto; background: #fff; box-shadow: 0 2px 10px rgba(0,0,0,0.06); }
  th, td { padding: 12px 14px; border-bottom: 1px solid #eee; text-align: left; vertical-align: middle; }
  th { background: #fafafa; font-weight: 600; }
  tr:hover td { background: #fcfcfe; }
  .term { font-weight: 600; transition: color 0.12s ease; }
  .term.speaking { color: #d92b2b; } /* đỏ khi đang phát */
  .play-btn {
    background: transparent;
    border: 1px solid #ddd;
    padding: 8px;
    border-radius: 8px;
    cursor: pointer;
    display:flex;
    align-items:center;
    gap:8px;
  }
  .play-btn:hover { border-color: #bbb; }
  .speaker-icon { width:18px; height:18px; display:inline-block; }
  caption { text-align:left; padding: 12px 14px; font-size: 16px; color: #333; }
  .note { max-width:1000px; margin:14px auto; font-size: 14px; color:#555; }
</style>
</head>
<body>

<table aria-describedby="note">
  <caption>15 thuật ngữ AI — bấm nút loa để nghe phát âm (tiếng Anh). Thuật ngữ chuyển <strong style="color:#d92b2b">màu đỏ</strong> khi đang phát.</caption>
  <thead>
    <tr>
      <th>Từ (English)</th>
      <th>Nghĩa (Tiếng Việt)</th>
      <th>Phát âm</th>
    </tr>
  </thead>
  <tbody id="terms-body">
    <tr>
      <td class="term">Artificial Intelligence</td>
      <td>Trí tuệ nhân tạo — hệ thống máy tính mô phỏng khả năng con người</td>
      <td><button class="play-btn" data-term="Artificial Intelligence" aria-label="Play Artificial Intelligence"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Machine Learning</td>
      <td>Máy học — thuật toán cho phép máy cải thiện qua dữ liệu</td>
      <td><button class="play-btn" data-term="Machine Learning" aria-label="Play Machine Learning"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Deep Learning</td>
      <td>Học sâu — dạng machine learning dùng mạng nơ-ron nhiều lớp</td>
      <td><button class="play-btn" data-term="Deep Learning" aria-label="Play Deep Learning"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Neural Network</td>
      <td>Mạng nơ-ron — mô hình tính toán lấy cảm hứng từ não sinh học</td>
      <td><button class="play-btn" data-term="Neural Network" aria-label="Play Neural Network"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Natural Language Processing</td>
      <td>Xử lý ngôn ngữ tự nhiên — máy hiểu và sinh ngôn ngữ người</td>
      <td><button class="play-btn" data-term="Natural Language Processing" aria-label="Play Natural Language Processing"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Computer Vision</td>
      <td>Thị giác máy tính — máy phân tích, hiểu hình ảnh và video</td>
      <td><button class="play-btn" data-term="Computer Vision" aria-label="Play Computer Vision"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Reinforcement Learning</td>
      <td>Học tăng cường — học bằng phần thưởng/khuyến khích trong môi trường</td>
      <td><button class="play-btn" data-term="Reinforcement Learning" aria-label="Play Reinforcement Learning"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Supervised Learning</td>
      <td>Học có giám sát — dùng dữ liệu đã gắn nhãn để huấn luyện</td>
      <td><button class="play-btn" data-term="Supervised Learning" aria-label="Play Supervised Learning"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Unsupervised Learning</td>
      <td>Học không giám sát — tìm cấu trúc trong dữ liệu chưa gắn nhãn</td>
      <td><button class="play-btn" data-term="Unsupervised Learning" aria-label="Play Unsupervised Learning"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Transfer Learning</td>
      <td>Học chuyển giao — tái dùng kiến thức từ bài toán này sang bài toán khác</td>
      <td><button class="play-btn" data-term="Transfer Learning" aria-label="Play Transfer Learning"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Generative AI</td>
      <td>AI sinh tạo — mô hình tạo ra văn bản, hình ảnh, âm thanh mới</td>
      <td><button class="play-btn" data-term="Generative AI" aria-label="Play Generative AI"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Transformer</td>
      <td>Kiến trúc mạng (Transformer) — nền tảng cho nhiều LLM và mô hình ngôn ngữ</td>
      <td><button class="play-btn" data-term="Transformer" aria-label="Play Transformer"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Large Language Model</td>
      <td>Mô hình ngôn ngữ lớn — mô hình có rất nhiều tham số để xử lý ngôn ngữ</td>
      <td><button class="play-btn" data-term="Large Language Model" aria-label="Play Large Language Model"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Overfitting</td>
      <td>Hiện tượng mô hình học quá kỹ dữ liệu huấn luyện, kém tổng quát</td>
      <td><button class="play-btn" data-term="Overfitting" aria-label="Play Overfitting"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
    <tr>
      <td class="term">Training Data</td>
      <td>Dữ liệu huấn luyện — tập dữ liệu dùng để đào tạo mô hình</td>
      <td><button class="play-btn" data-term="Training Data" aria-label="Play Training Data"><svg class="speaker-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 9v6h4l5 5V4L9 9H5z" stroke="#333" stroke-width="1.2" stroke-linejoin="round" stroke-linecap="round"/></svg>Play</button></td>
    </tr>
  </tbody>
</table>

<div id="note" class="note">
  <strong>Lưu ý:</strong> Nếu trình duyệt của bạn hỏi quyền âm thanh, hãy cho phép. Chất giọng, ngữ điệu do trình duyệt cung cấp (Web Speech API) — bạn có thể thay <code>voiceLang</code> trong mã xuống <code>en-GB</code> hoặc các giọng khác nếu muốn.
</div>

<script>
(function(){
  const buttons = document.querySelectorAll('.play-btn');
  const synth = window.speechSynthesis;
  // mặc định dùng giọng en-US nếu có
  const voiceLang = 'en-US';

  function findVoice() {
    const voices = synth.getVoices ? synth.getVoices() : [];
    // find suitable voice by lang prefix
    return voices.find(v => v.lang && v.lang.toLowerCase().startsWith(voiceLang.toLowerCase())) || voices[0] || null;
  }

  // handle dynamic voice list load in some browsers
  let selectedVoice = findVoice();
  if (!selectedVoice) {
    window.speechSynthesis.onvoiceschanged = () => {
      selectedVoice = findVoice();
    };
  }

  buttons.forEach(btn => {
    btn.addEventListener('click', () => {
      const text = btn.getAttribute('data-term') || btn.dataset.term;
      if (!text) return;
      // cancel any running utterances
      synth.cancel();

      const tr = btn.closest('tr');
      const termCell = tr.querySelector('.term');
      // create utterance
      const u = new SpeechSynthesisUtterance(text);
      if (selectedVoice) u.voice = selectedVoice;
      u.rate = 0.95; // tốc độ hơi chậm cho rõ
      u.pitch = 1.0;

      u.onstart = () => {
        termCell.classList.add('speaking'); // đổi đỏ
        btn.disabled = true;
        btn.style.opacity = 0.9;
      };
      u.onend = u.onerror = () => {
        termCell.classList.remove('speaking');
        btn.disabled = false;
        btn.style.opacity = 1;
      };
      synth.speak(u);
    });
  });
})();
</script>

</body>
</html>
