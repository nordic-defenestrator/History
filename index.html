<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Webで学ぶ！近代世界の歩み</title>
<style>
  /* --- 基本デザイン --- */
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&display=swap');
  body { font-family: 'Noto Sans JP', sans-serif; background-color: #f4f7f6; color: #333; line-height: 1.6; margin: 0; padding: 10px; overflow-x: hidden; }
  .container { max-width: 800px; margin: 0 auto; background: #fff; box-shadow: 0 4px 15px rgba(0,0,0,0.1); border-radius: 12px; overflow: hidden; }
  header { background: linear-gradient(135deg, #2c3e50, #3498db); color: #fff; text-align: center; padding: 30px 15px; }
  header h1 { margin: 0; font-size: 1.6rem; }
  header p { margin: 10px 0 0; font-size: 0.9rem; opacity: 0.9; }

  section { padding: 25px 20px; border-bottom: 2px dashed #ecf0f1; }
  section:last-child { border-bottom: none; }
  h2 { color: #2c3e50; border-left: 6px solid #e74c3c; padding-left: 12px; margin-top: 0; font-size: 1.4rem; }
  h3 { color: #2980b9; border-bottom: 1px solid #bdc3c7; padding-bottom: 5px; margin-top: 25px; }
  p { margin-bottom: 15px; }
  .highlight { background: linear-gradient(transparent 60%, #ffeaa7 60%); font-weight: bold; color: #2c3e50; }
  .cause-result { background: #f0f8ff; padding: 15px; border-radius: 8px; margin: 15px 0; border-left: 5px solid #3498db; }
  details { background: #fdf2e9; padding: 12px; border-radius: 8px; margin: 15px 0; border: 1px solid #fad7a1; cursor: pointer; }
  summary { font-weight: bold; color: #d35400; font-size: 1.1rem; outline: none; }
  .details-content { margin-top: 10px; font-size: 0.95rem; color: #555; }
  .img-container { text-align: center; margin: 20px 0; }
  .img-container img { max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.15); max-height: 250px; object-fit: cover; }

  .vs-box { display: flex; justify-content: space-between; align-items: center; background: #f8f9fa; padding: 15px; border-radius: 10px; margin: 20px 0; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
  .vs-team { flex: 1; text-align: center; padding: 15px 5px; border-radius: 8px; font-weight: bold; line-height: 1.8; }
  .team-a { background: #fadbd8; color: #c0392b; border-top: 4px solid #e74c3c; }
  .team-b { background: #d6eaf8; color: #2980b9; border-top: 4px solid #3498db; }
  .vs-mark { font-size: 1.5rem; font-weight: bold; color: #7f8c8d; margin: 0 10px; font-style: italic; }

  /* --- ビジュアル年表のデザイン --- */
  .timeline { position: relative; max-width: 100%; margin: 20px 0; padding-left: 10px; }
  .timeline::after { content: ''; position: absolute; width: 4px; background-color: #3498db; top: 0; bottom: 0; left: 16px; border-radius: 2px; }
  .timeline-item { padding: 10px 0 10px 40px; position: relative; }
  .timeline-item::after { content: ''; position: absolute; width: 14px; height: 14px; background-color: #fff; border: 4px solid #e74c3c; top: 18px; left: 7px; border-radius: 50%; z-index: 1; }
  .timeline-content { padding: 10px 15px; background-color: #fdf2e9; border-radius: 6px; border-left: 4px solid #e67e22; font-size: 0.95rem; }
  .timeline-year { font-weight: bold; color: #d35400; font-size: 1.1rem; margin-right: 5px; }

  /* --- ここからゲーム＆引き出し用デザイン --- */
  .drawer-area { display: flex; gap: 10px; margin: 20px 0; justify-content: center; }
  .drawer-btn { background: #8b5a2b; color: #fff; padding: 15px 20px; border-radius: 5px; cursor: pointer; font-weight: bold; box-shadow: 0 4px 0 #5c3a21; transition: 0.1s; text-align: center; flex: 1; }
  .drawer-btn:active { transform: translateY(4px); box-shadow: none; }
  .danger-drawer { background: #c0392b; box-shadow: 0 4px 0 #7b241c; }
  
  /* STGオーバーレイ */
  #game-overlay { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(30, 0, 0, 0.98); z-index: 9999; overflow: hidden; touch-action: none; transition: box-shadow 0.2s; }
  
  /* ボスHPバー（画面上部） */
  #boss-hp-container { position: absolute; top: 20px; left: 10%; width: 80%; height: 15px; background: #333; border: 2px solid #ffd700; border-radius: 10px; z-index: 10001; }
  #boss-hp-bar { width: 100%; height: 100%; background: linear-gradient(90deg, #ff4e50, #f9d423); transition: width 0.1s; }
  #boss-name { position: absolute; top: -18px; left: 0; color: #ffd700; font-size: 12px; font-weight: bold; }

  /* プレイヤー（自機）と頭上ミニHPバー */
  #player-container { position: absolute; width: 60px; height: 80px; transform: translate(-50%, -50%); z-index: 10000; pointer-events: none; }
  #player-sprite { font-size: 40px; text-align: center; text-shadow: 0 0 15px #fff; }
  #player-hp-mini { width: 40px; height: 5px; background: #333; border: 1px solid #fff; margin: 0 auto; border-radius: 3px; overflow: hidden; }
  #player-hp-bar { width: 100%; height: 100%; background: #2ecc71; transition: background 0.2s, width 0.2s; }

  /* 敵 (ボス: ☭) */
  #ussr-enemy { position: absolute; font-size: 80px; color: #ffd700; transform: translate(-50%, -50%); text-shadow: 0 0 20px #ff0000; z-index: 9999; transition: left 0.5s ease-out, top 0.5s ease-out; }

  /* 弾幕・アイテムパーツ */
  .e-bullet { position: absolute; font-size: 25px; color: #ff5555; pointer-events: none; z-index: 9998; text-shadow: 0 0 5px #f1c40f; } /* 敵弾 ★ */
  .p-bullet { position: absolute; font-size: 24px; color: #55aaff; pointer-events: none; z-index: 9997; text-shadow: 0 0 10px #fff; } /* 自機弾 ✞ */
  .h-item { position: absolute; font-size: 30px; pointer-events: none; z-index: 9997; filter: drop-shadow(0 0 5px #2ecc71); } /* 回復アイテム 🍙 */
  .beam { position: absolute; background: linear-gradient(to bottom, transparent, #ff0000, #fff, #ff0000, transparent); width: 100vw; height: 80px; z-index: 9998; opacity: 0; transition: opacity 0.2s; pointer-events: none; }

  .holy-light { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 200vw; height: 200vh; background: radial-gradient(circle, rgba(255,255,255,1) 0%, rgba(255,255,210,0.8) 30%, rgba(150,0,0,0) 70%); opacity: 0; pointer-events: none; transition: opacity 0.5s ease; z-index: 10000; }
  
  @keyframes shake { 0%, 100% { transform: translate(0, 0) rotate(0deg); } 10%, 30%, 50%, 70%, 90% { transform: translate(-5px, -5px) rotate(-2deg); } 20%, 40%, 60%, 80% { transform: translate(5px, 5px) rotate(2deg); } }
  .shake-screen { animation: shake 0.3s; }
  
  footer { background: #2c3e50; color: #ecf0f1; text-align: center; padding: 20px; font-size: 0.9rem; }
</style>
</head>
<body>

<div class="container">
  <header>
    <h1>Webで学ぶ！近代世界の歩み</h1>
    <p>〜帝国主義からファシズムの台頭まで〜</p>
  </header>

  <!-- 👇ビジュアル年表👇 -->
  <section style="background-color: #fafafa;">
    <h2>近代史 ビジュアル年表</h2>
    <p>これから学ぶ時代の大きな流れを掴もう！</p>
    <div class="timeline">
      <div class="timeline-item"><div class="timeline-content"><span class="timeline-year">1894年</span> 日清戦争勃発・領事裁判権の廃止</div></div>
      <div class="timeline-item"><div class="timeline-content"><span class="timeline-year">1904年</span> 日露戦争勃発</div></div>
      <div class="timeline-item"><div class="timeline-content"><span class="timeline-year">1911年</span> 関税自主権の回復・辛亥革命</div></div>
      <div class="timeline-item"><div class="timeline-content"><span class="timeline-year">1914年</span> 第一次世界大戦勃発（サラエボ事件）</div></div>
      <div class="timeline-item"><div class="timeline-content"><span class="timeline-year">1925年</span> 普通選挙法・治安維持法の制定</div></div>
      <div class="timeline-item"><div class="timeline-content"><span class="timeline-year">1929年</span> 世界恐慌</div></div>
    </div>
  </section>

  <!-- 第1章 -->
  <section>
    <h2>1. 帝国主義と日本の条約改正</h2>
    <p>欧米諸国は、海外進出や発展中の植民地支配を目指しました（<span class="highlight">帝国主義</span>）。</p>
    <h3>不平等条約への苦難</h3>
    <div class="cause-result">
      <strong>岩倉使節団の影響と欧化政策</strong><br>
      外務卿の<span class="highlight">井上馨</span>が欧米人を「鹿鳴館」に招いて欧化政策を行うも失敗。<br>
      1886年には<strong>ノルマントン号事件</strong>が発生。日本人乗客らが助からなかったのに、イギリス人船長を日本で裁けず、<span class="highlight">領事裁判権の廃止</span>を求める声が爆発しました。
    </div>
    <div class="img-container">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Mutsu_Munemitsu.jpg" alt="陸奥宗光">
      <p style="font-size: 0.8rem; color: #7f8c8d;">条約改正に尽力した陸奥宗光</p>
    </div>
    <h3>条約改正の実現！</h3>
    <ul>
      <li><strong>1894年：</strong><span class="highlight">陸奥宗光</span>（外相）が<strong>日英通商航海条約</strong>を結び、領事裁判権の廃止に成功！</li>
      <li><strong>1911年：</strong><span class="highlight">小村寿太郎</span>（外相）が日米通商航海条約を結び、<strong>関税自主権の回復</strong>を達成！</li>
    </ul>
  </section>

  <!-- 第2章 -->
  <section>
    <h2>2. 日清・日露戦争とアジアの激動</h2>
    <p>19世紀末、1894年に<strong>甲午農民戦争</strong>が勃発。これを機に日本と清が対立しました。</p>
    <div class="cause-result">
      <strong>日清戦争（1894年）と三国干渉</strong><br>
      日本が勝利し、1895年に<span class="highlight">下関条約</span>を締結。<br>
      しかし、ロシア等の<strong>三国干渉</strong>で遼東半島を返還させられ、対ロシアへの不満が高まりました。
    </div>
<div class="cause-result">
      <strong>日露戦争（1904年）</strong><br>
      東郷平八郎らの活躍で勝利し、アメリカの仲介で<span class="highlight">ポーツマス条約</span>を締結。<br>
      【得たもの】<strong>南樺太</strong>、<strong>旅順・大連の租借権</strong>、南満州鉄道の利権<br>
      【得られなかったもの】賠償金（※これにより政府への不満が爆発し、<strong>日比谷焼打事件</strong>が発生！）
    </div>
    <details>
      <summary>🔥 テスト発狂案件：韓国併合と辛亥革命</summary>
      <div class="details-content">
        <ul>
          <li><strong>韓国併合：</strong>1905年に韓国を保護国化。1910年に<span class="highlight">韓国併合</span>を行いました。</li>
          <li><strong>辛亥革命：</strong>清を倒すため、<strong>孫文</strong>が運動。1912年に<span class="highlight">中華民国</span>が誕生し、清は滅亡！</li>
        </ul>
      </div>
    </details>
  </section>

  <!-- 第3章 -->
  <section>
    <h2>3. 日本の産業革命と近代文化</h2>
    <p>日清戦争の賠償金をもとに、<span class="highlight">八幡製鉄所</span>が建設され、重工業が発展！三井・三菱などの実業家は<strong>財閥</strong>と呼ばれました。</p>
    <div class="cause-result">
      <strong>発展の裏の社会問題</strong><br>
      ・<span class="highlight">田中正造</span>：足尾銅山鉱毒事件で天皇に直訴。<br>
      ・<span class="highlight">大逆事件</span>（1910年）：幸徳秋水ら社会主義者が処刑される。
    </div>
    <h3>近代文化のオールスターズ</h3>
    <ul>
      <li><strong>美術：</strong>フェノロサと<span class="highlight">岡倉天心</span>、横山大観、黒田清輝</li>
      <li><strong>文学：</strong>夏目漱石、森鴎外、樋口一葉</li>
      <li><strong>医学：</strong><span class="highlight">北里柴三郎</span>（ペスト菌）、<span class="highlight">野口英世</span>（黄熱病）、<span class="highlight">志賀潔</span>（赤痢菌）</li>
    </ul>
  </section>

  <!-- 第4章 -->
  <section>
    <h2>4. 第一次世界大戦とロシア革命</h2>
    <div class="vs-box">
      <div class="vs-team team-a">【三国同盟】<br>🇩🇪 ドイツ<br>🇦🇹 オーストリア<br>🇮🇹 イタリア</div>
      <div class="vs-mark">VS</div>
      <div class="vs-team team-b">【三国協商】<br>🇬🇧 イギリス<br>🇫🇷 フランス<br>🇷🇺 ロシア</div>
    </div>
    <p>バルカン半島（ヨーロッパの火薬庫）での<strong>サラエボ事件</strong>を機に<span class="highlight">第一次世界大戦</span>が勃発。</p>
    <div class="cause-result">
      <strong>ロシア革命とシベリア出兵（1917年〜）</strong><br>
      レーニン率いるソビエト政権が誕生。日本などは<span class="highlight">シベリア出兵</span>を行うも失敗。日本では<strong id="kome-btn" onclick="dropKome()" style="cursor:pointer; color:#e74c3c; text-decoration:underline;">米騒動（タップ！）</strong>が全国に波及！
    </div>
    <p>1919年、<span class="highlight">ベルサイユ条約</span>が結ばれ、翌年<strong>国際連盟</strong>が設立されますが、アメリカは不参加という罠！</p>
    <div class="cause-result" style="border-left-color: #27ae60; background: #e9f7ef;">
      <strong>アジアの民族独立運動（1919年）</strong><br>
      ・朝鮮：日本からの独立を求める<span class="highlight">三・一独立運動</span><br>
      ・中国：二十一カ条の要求取り消しを求める<span class="highlight">五・四運動</span><br>
      ・インド：ガンジーによる非暴力・不服従運動
    </div>
    <p>その後、1921〜22年の<strong>ワシントン会議</strong>で、海軍の軍備縮小や日英同盟の解消が決まり、一時的に国際協調（平和）のムードが高まりました。</p>
  </section>

  <!-- 第5章 -->
  <section>
    <h2>5. 大正デモクラシーと大衆文化</h2>
    <h3>護憲運動と政党内閣の誕生</h3>
    <p>桂太郎内閣に対し<strong>「護憲運動」</strong>が起きます。</p>
    <div class="cause-result">
      ・政治学者の<strong>吉野作造</strong>が<span class="highlight">民本主義</span>を唱えました。<br>
      ・立憲政友会の<span class="highlight">原敬</span>が内閣を組織。<strong>本格的な政党内閣</strong>が誕生しました。
    </div>
    <div class="cause-result" style="border-left-color: #e67e22;">
      <strong>⚠️ 1925年の「アメとムチ」コンボ（超重要！）</strong><br>
      【アメ】<span class="highlight">普通選挙法</span>：25歳以上の全ての男子に選挙権！<br>
      【ムチ】<span class="highlight">治安維持法</span>：社会主義運動を厳しく弾圧！
    </div>
    <ul>
      <li><strong>女性運動：</strong>1911年、<span class="highlight">平塚らいてう</span>らが青鞜社を結成。</li>
      <li><strong>労働・農民運動：</strong>労働組合による労働争議、小作人による小作争議が起きました。</li>
      <li><strong>部落解放運動：</strong>1922年、被差別部落の人々が自ら<span class="highlight">全国水平社</span>を結成！</li>
    </ul>
    <p>1923年の<strong>関東大震災</strong>を機に鉄筋コンクリートの建物が増え、<strong>ラジオ放送</strong>もスタートしました。</p>
  </section>

  <!-- 第6章 -->
  <section>
    <h2>6. 世界恐慌とファシズムの台頭</h2>
    <p>1929年10月、ニューヨークの株価大暴落をきっかけに<span class="highlight">世界恐慌</span>が発生。</p>
    <details>
      <summary>💡 公民の知識とリンク！各国の対策</summary>
      <div class="details-content">
        <ul>
          <li><strong>アメリカ：</strong><span class="highlight">ニューディール政策</span>。政府が公共事業を行い景気を回復！</li>
          <li><strong>イギリス・フランス：</strong><span class="highlight">ブロック経済</span>。植民地を囲い込み、関税で締め出し！</li>
          <li><strong>ソ連：</strong><span class="highlight">五カ年計画</span>。計画経済のため、世界恐慌のダメージを受けず！</li>
          <li><strong>【おまけ】ドイツの悲劇：</strong>1919年に世界初の社会権を保障した<span class="highlight">ワイマール憲法</span>が作られましたが、ヒトラー（ナチ党）が独裁を始めると完全に無視されてしまいました…。</li>
        </ul>
      </div>
    </details>
    <div class="img-container">
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/FDR_in_1933.jpg" alt="ルーズベルト大統領">
    </div>
    <h3>ファシズムの台頭</h3>
    <p>イタリアでは<strong>ムッソリーニ</strong>、ドイツでは<strong>ヒトラー</strong>が政権を握り、世界は再び戦争への道を歩み始めます……。</p>
  </section>

  <!-- 👇 ルーズベルト注意書き👇 -->
  <section style="background-color: #fff3cd;">
    <h2 style="border-left-color: #d35400; color: #d35400;">⚠️ サイト管理人からの重要なお知らせ</h2>
    <p style="font-weight: bold; color: #c0392b;">※当サイトを読む際の注意：第2章のルーズベルトと第6章のルーズベルトは別人（親戚）です。間違えると日露戦争の講和会議に車椅子で乗り込むことになります。</p>
    
    <div style="display: flex; justify-content: center; align-items: center; gap: 15px; margin-top: 20px;">
      <div style="text-align: center; flex: 1;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Theodore_Roosevelt_circa_1902.jpg" alt="セオドア・ルーズベルト" style="width: 100%; max-width: 150px; height: 150px; border-radius: 8px; object-fit: cover; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        <p style="font-size: 0.8rem; font-weight: bold; margin-top: 5px;">【第2章】セオドア<br><span style="font-weight: normal; color: #555;">(日露戦争の仲介者)</span></p>
      </div>
      <div style="font-size: 1.5rem; font-weight: bold; color: #e74c3c;">VS</div>
      <div style="text-align: center; flex: 1;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/FDR_in_1933.jpg" alt="フランクリン・ルーズベルト" style="width: 100%; max-width: 150px; height: 150px; border-radius: 8px; object-fit: cover; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        <p style="font-size: 0.8rem; font-weight: bold; margin-top: 5px;">【第6章】フランクリン<br><span style="font-weight: normal; color: #555;">(ニューディール政策)</span></p>
      </div>
    </div>
    <p style="font-size: 0.85rem; color: #555; margin-top: 10px;">名前が同じ「ルーズベルト大統領」なので、テストの解答欄にフルネームで書かないと減点される（時代が30年ワープして歴史が崩壊する）超特大トラップです。気をつけましょう！</p>
  </section>

  <!-- おまけ：秘密の資料室 -->
  <section style="background-color: #eee;">
    <h2 style="border-left-color: #8e44ad; color: #8e44ad;">秘密の資料室（おまけ）</h2>
    <p>当時の貴重な資料が保管されています。引き出しをタップしてみてね。</p>
    <div class="drawer-area">
      <div class="drawer-btn" onclick="alert('【伊藤博文のヒゲのお手入れセット】が出てきた！\n\n…そっと戻した。')">引き出し①</div>
      <div class="drawer-btn" onclick="alert('【夏目漱石のネコの落書き】が出てきた！\n\n…ちょっとかわいい。')">引き出し②</div>
      <div class="drawer-btn danger-drawer" id="btn-danger">⚠️ 引いちゃダメ</div>
    </div>
  </section>

</div>

<footer>
  <p>© 2024 オリジナル歴史まとめWebノート | Designed with ❤️ & Code</p>
</footer>

<!-- 👇ソ連亡霊アクションゲーム（HP増幅＆回復アイテム追加版！）👇 -->
<div id="game-overlay">
  <!-- ボスHPバー -->
  <div id="boss-hp-container">
    <div id="boss-name">THE SOVIET SPECTER (ソ連の亡霊)</div>
    <div id="boss-hp-bar"></div>
  </div>

  <div id="ussr-enemy">☭</div>
  
  <!-- 自機（✞）と頭上のミニHPバー -->
  <div id="player-container">
    <div id="player-hp-mini"><div id="player-hp-bar"></div></div>
    <div id="player-sprite">✞</div>
  </div>
  
  <div id="bullets-container"></div> <!-- 弾（★と✞）やアイテム（🍙）が生成される場所 -->
  <div id="beam-effect" class="beam"></div> <!-- 極太ビーム用 -->
  <div id="holy-light" class="holy-light"></div>
</div>

<script>
  // 🌾 米騒動エフェクト（1回きり）の魔法
  let isKomeDropped = false;
  function dropKome() {
    if (isKomeDropped) return; 
    isKomeDropped = true;

    let btn = document.getElementById('kome-btn');
    btn.style.cursor = 'default';
    btn.style.textDecoration = 'none';
    btn.style.color = 'inherit';
    btn.innerText = '米騒動'; 

    let bale = document.createElement('div');
    bale.style.cssText = 'position:fixed; top:-100px; left:50%; transform:translateX(-50%); width:100px; height:60px; background:#d3b88c; border:4px solid #8b5a2b; border-radius:15px; text-align:center; line-height:50px; font-weight:bold; font-size:30px; color:#5c3a21; z-index:10000; box-shadow: 0 10px 20px rgba(0,0,0,0.5);';
    bale.innerText = '米';
    document.body.appendChild(bale);

    bale.animate([
      { top: '-100px', animationTimingFunction: 'ease-in' },
      { top: '50%', animationTimingFunction: 'ease-out', offset: 0.6 },
      { top: '35%', animationTimingFunction: 'ease-in', offset: 0.8 },
      { top: '50%', offset: 1 } 
    ], { duration: 800, fill: 'forwards' }).onfinish = () => {
      
      bale.remove();
      document.body.classList.add('shake-screen');
      setTimeout(() => document.body.classList.remove('shake-screen'), 300);

      for(let i = 0; i < 20; i++) {
        let rice = document.createElement('div');
        rice.innerText = '🍚';
        rice.style.cssText = 'position:fixed; top:50%; left:50%; font-size:40px; z-index:9999; pointer-events:none;';
        document.body.appendChild(rice);

        let angle = Math.random() * Math.PI * 2;
        let speed = Math.random() * 200 + 100;
        let vx = Math.cos(angle) * speed;
        let vy = Math.sin(angle) * speed;

        rice.animate([
          { transform: 'translate(-50%, -50%) scale(1)', opacity: 1 },
          { transform: `translate(calc(-50% + ${vx}px), calc(-50% + ${vy}px)) scale(1.5) rotate(${Math.random()*360}deg)`, opacity: 0 }
        ], { duration: 600 + Math.random() * 400, easing: 'ease-out', fill: 'forwards' }).onfinish = () => rice.remove();
      }
    };
  }

  // 🎮 ソ連除霊・弾幕STGの魔法（HP増幅＆回復アイテム追加！）
  const dangerBtn = document.getElementById('btn-danger');
  const gameOverlay = document.getElementById('game-overlay');
  const enemy = document.getElementById('ussr-enemy');
  const playerContainer = document.getElementById('player-container');
  const light = document.getElementById('holy-light');
  const pBar = document.getElementById('player-hp-bar');
  const bBar = document.getElementById('boss-hp-bar');
  const bulletsContainer = document.getElementById('bullets-container');
  const beam = document.getElementById('beam-effect');
  const ussrAnthem = new Audio('https://upload.wikimedia.org/wikipedia/commons/a/a2/National_Anthem_of_the_Soviet_Union_%281944-1955%29.oga');
  
  let isGameOver = false, isPressing = false;
  // ★主人公の最大HPを200に倍増！
  let maxPlayerHp = 200; 
  let playerHp = maxPlayerHp, bossHp = 1000;
  let eBullets = [], pBullets = [], items = [];
  let gameTimer, gameLoopId;
  let playerX = -1000, playerY = -1000;
  let enemyX = window.innerWidth / 2, enemyY = window.innerHeight / 2;
  let frame = 0;

  // プレイヤーの移動
  function movePlayer(x, y) {
    if (isGameOver) return;
    playerX = x; playerY = y;
    playerContainer.style.left = playerX + 'px'; playerContainer.style.top = playerY + 'px';
  }
  gameOverlay.addEventListener('mousemove', (e) => movePlayer(e.clientX, e.clientY));
  gameOverlay.addEventListener('touchmove', (e) => { 
    e.preventDefault(); movePlayer(e.touches[0].clientX, e.touches[0].clientY); 
  }, { passive: false });
  
  gameOverlay.addEventListener('mousedown', () => isPressing = true);
  gameOverlay.addEventListener('mouseup', () => isPressing = false);
  gameOverlay.addEventListener('touchstart', () => isPressing = true);
  gameOverlay.addEventListener('touchend', () => isPressing = false);

  // ゲームスタート
  dangerBtn.addEventListener('click', () => {
    isGameOver = false; playerHp = maxPlayerHp; bossHp = 1000; frame = 0;
    pBar.style.width = '100%'; bBar.style.width = '100%';
    pBar.style.background = '#2ecc71';
    bulletsContainer.innerHTML = ''; eBullets = []; pBullets = []; items = [];
    playerX = -1000; playerY = -1000; 
    
    clearInterval(gameTimer); cancelAnimationFrame(gameLoopId);
    ussrAnthem.volume = 0.5; ussrAnthem.currentTime = 0; ussrAnthem.play().catch(() => {});
    
    gameOverlay.style.display = 'block'; enemy.style.opacity = 1; light.style.opacity = 0;
    
    gameTimer = setInterval(() => {
      if (isGameOver) return;
      enemyX = Math.random() * (window.innerWidth - 100) + 50; 
      enemyY = Math.random() * (window.innerHeight / 2 - 50) + 50; 
      enemy.style.left = enemyX + 'px'; enemy.style.top = enemyY + 'px';
    }, 800); 

    function loop() {
      if (isGameOver) return;
      frame++;

      // 1. 自機の連射 (✞)
      if (frame % 5 === 0 && isPressing && playerY > 0) {
        let el = document.createElement('div');
        el.className = 'p-bullet'; el.innerText = '✞';
        bulletsContainer.appendChild(el);
        pBullets.push({ el: el, x: playerX, y: playerY - 40, vy: -15 });
      }

      // 2. 敵の弾幕 (★)
      if (frame % 30 === 0 && playerX !== -1000) {
        let bulletCount = bossHp < 500 ? 12 : 6; 
        for (let i = 0; i < bulletCount; i++) {
          let angle = (i / bulletCount) * Math.PI * 2 + (frame * 0.05);
          let el = document.createElement('div');
          el.className = 'e-bullet'; el.innerText = '★';
          bulletsContainer.appendChild(el);
          eBullets.push({ el: el, x: enemyX, y: enemyY, vx: Math.cos(angle) * 5, vy: Math.sin(angle) * 5 });
        }
      }

      // 3. ボスの発狂ビーム
      if (bossHp < 500 && frame % 180 === 0 && playerX !== -1000) {
        beam.style.top = (playerY - 40) + 'px'; 
        beam.style.opacity = 0.5; 
        setTimeout(() => {
          if (isGameOver) return;
          beam.style.opacity = 1; 
          if (Math.abs(playerY - parseFloat(beam.style.top) - 40) < 50) damagePlayer(40); 
          setTimeout(() => beam.style.opacity = 0, 300);
        }, 600);
      }

      // ★4. 回復アイテム（🍙）の投下！（約4秒に1回）
      if (frame % 250 === 0 && playerX !== -1000) {
        let el = document.createElement('div');
        el.className = 'h-item'; el.innerText = '🍙';
        bulletsContainer.appendChild(el);
        items.push({ el: el, x: Math.random() * (window.innerWidth - 50) + 25, y: -50, vy: 4 });
      }

      // 自機弾(✞)の移動＆ダメージ判定
      for (let i = pBullets.length - 1; i >= 0; i--) {
        let b = pBullets[i];
        b.y += b.vy; b.el.style.left = b.x + 'px'; b.el.style.top = b.y + 'px';
        if (Math.abs(b.x - enemyX) < 40 && Math.abs(b.y - enemyY) < 40) {
          b.el.remove(); pBullets.splice(i, 1); damageBoss(); 
        } else if (b.y < -50) {
          b.el.remove(); pBullets.splice(i, 1); 
        }
      }

      // 敵弾(★)の移動＆ダメージ判定
      for (let i = eBullets.length - 1; i >= 0; i--) {
        let b = eBullets[i];
        b.x += b.vx; b.y += b.vy; b.el.style.left = b.x + 'px'; b.el.style.top = b.y + 'px';
        if (Math.abs(b.x - playerX) < 20 && Math.abs(b.y - playerY) < 20) {
          b.el.remove(); eBullets.splice(i, 1); damagePlayer(20); 
        } else if (b.y > window.innerHeight || b.y < 0 || b.x < 0 || b.x > window.innerWidth) {
          b.el.remove(); eBullets.splice(i, 1); 
        }
      }

      // ★アイテム(🍙)の移動＆回復判定
      for (let i = items.length - 1; i >= 0; i--) {
        let item = items[i];
        item.y += item.vy; item.el.style.left = item.x + 'px'; item.el.style.top = item.y + 'px';
        
        if (Math.abs(item.x - playerX) < 40 && Math.abs(item.y - playerY) < 40) {
          // キャッチして回復！
          item.el.remove(); items.splice(i, 1);
          playerHp = Math.min(maxPlayerHp, playerHp + 40); // 40回復（最大値を超えない）
          pBar.style.width = (playerHp / maxPlayerHp * 100) + '%';
          if (playerHp > maxPlayerHp * 0.4) pBar.style.background = '#2ecc71'; // ピンチ脱出で緑に戻る
          
          // 回復エフェクト（画面が一瞬緑に光る）
          gameOverlay.style.boxShadow = "inset 0 0 50px #2ecc71";
          setTimeout(() => gameOverlay.style.boxShadow = "none", 200);
        } else if (item.y > window.innerHeight) {
          item.el.remove(); items.splice(i, 1); 
        }
      }

      gameLoopId = requestAnimationFrame(loop);
    }
    loop(); 
  });

  function damageBoss() {
    if (isGameOver) return;
    bossHp -= 10;
    bBar.style.width = (bossHp / 10) + '%';
    if (bossHp <= 0) exorcise(); 
  }

  function damagePlayer(dmg) {
    if (isGameOver) return;
    playerHp -= dmg; 
    pBar.style.width = Math.max(0, (playerHp / maxPlayerHp) * 100) + '%'; // 割合計算を修正
    
    gameOverlay.classList.add('shake-screen');
    setTimeout(() => gameOverlay.classList.remove('shake-screen'), 300);
    
    if (playerHp <= maxPlayerHp * 0.4) pBar.style.background = '#e74c3c'; // HP40%以下で赤
    if (playerHp <= 0) gameOver();
  }

  function gameOver() {
    isGameOver = true; clearInterval(gameTimer); cancelAnimationFrame(gameLoopId); ussrAnthem.pause();
    alert('HPが0になった……\n\n【GAME OVER】\nシベリア送りにされました。');
    gameOverlay.style.display = 'none';
  }

  function exorcise() {
    isGameOver = true; clearInterval(gameTimer); cancelAnimationFrame(gameLoopId); ussrAnthem.pause();
    light.style.opacity = 1; enemy.style.opacity = 0;
    setTimeout(() => {
      light.style.opacity = 0; gameOverlay.classList.add('shake-screen');
      setTimeout(() => {
        alert('成仏した……\n\n【CLEAR おめでとう！！】\n（※報酬は特にありません）');
        gameOverlay.style.display = 'none'; gameOverlay.classList.remove('shake-screen');
      }, 600);
    }, 500);
  }
</script>
</body>
</html>
