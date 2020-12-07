<template>
  <div class="block timeline-wrapper">
    <el-timeline>
      <el-timeline-item id="bakutan" timestamp="爆誕" placement="top" class="timeline">
        <div class="timeline__cover">
          <span class="iconify" data-icon="twemoji:baby" data-inline="false"></span>
        </div>
        <div>
          <p>宮崎県宮崎市に生まれる。命名を「マリ」か「マリコ」で迷ったらしいが、国際化社会を見据えて「マリ」と名付けたらしい。</p>
          <p>誕生日が同じ人は高田賢三、パーク・マンサー、グッチ裕三</p>
        </div>
      </el-timeline-item>

      <el-timeline-item id="kids" timestamp="保育園" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:child-medium-skin-tone" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>おままごとよりもヒーローごっこに夢中だった。将来の夢はセーラームーンと発表したのをバカにされて号泣。おでこにでっかい切り傷ができたのもこの頃。</p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-button type="success" size="mini" plain round>#セーラームーン</el-button>
              <el-button type="success" size="mini" plain round>#カクレンジャー</el-button>
              <el-button type="success" size="mini" plain round>#サイダーゼリー</el-button>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="elementary" timestamp="小学校" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:name-badge" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>この頃からお絵かきに目覚める。親戚の漫画コレクションや図鑑を読み漁る日々。</p>
            <p>学校ではwindows95が導入され、アニメーションを作る課外授業で感動。パソコンで何か作ることへの興味の原点はここかもしれない。</p>
            <p>お母さんに勝手に空手道場に入門させられて泣きながら通っていたが、なんとか黒帯をゲットする。</p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-link href="https://twitter.com/EISAKUSAKU" target="_blank" :underline="false" type="success">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:twitter"
                    data-inline="false"></span>ツルモク独身寮</el-button>
              </el-link>
              <el-button type="success" size="mini" plain round>#スラムダンク</el-button>
              <el-button type="success" size="mini" plain round>#ドラえもん</el-button>
              <el-button type="success" size="mini" plain round>#GLAY</el-button>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="jhs" timestamp="中学校" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:alien" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>ゴトウ、オシャレに目覚める。が、オシャレとはなんなのか手探り状態だったので、上下赤チェックの格好で堂々と街中を歩いたりしていた。オシャレな子はハイスタやアヴリルを聴いていた。</p>
            <p>FFⅨと資生堂のCMが好きで、将来はどっちかの会社に入るんだと意気込んでいた。</p>
            <p>初めての告白を経験したのもこの頃。（結果は玉砕）</p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-button type="success" size="mini" plain round>#RIP SLYME</el-button>
              <el-button type="success" size="mini" plain round>#うたばん</el-button>
              <el-link class="tag__link" type="success" :underline="false" target="_blank"
                href="https://youtu.be/FsDzX2YVxNY">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:youtube"
                    data-inline="false"></span>資生堂 UV WHITE</el-button>
              </el-link>
              <el-button type="success" size="mini" plain round>#もののけ姫</el-button>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="hs" timestamp="高校" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:artist-palette" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>高校受験に失敗し、滑り止めの私立高校の芸術学科へ入学。</p>
            <p>画材使い放題・美術室入り浸り放題という、今思うとありがたすぎる環境でひたすら制作に勤しむ。</p>
            <p>小中と違い好きな時間に好きなだけ食べれるので、ブクブク太りだしたのもこの頃。ダイエットとの付き合いの始まり。</p>
            <p>FFⅨと資生堂のCMが好きで、将来はどっちかの会社に入るんだと意気込んでいた。</p>
            <p>初めて東京に来たのも高校生のとき。修学旅行も東京で、当時オープンしたばかりの六本木ヒルズでトイカメラセットを買った思い出。</p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-link href="https://www.plus81.com/" target="_blank" :underline="false" type="success">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="twemoji:notebook"
                    data-inline="false"></span>+81</el-button>
              </el-link>
              <el-link href="http://www.tadanoriyokoo.com/" target="_blank" :underline="false" type="success">
                <el-button type="success" size="mini" round><span class="iconify"
                    data-icon="twemoji:man-in-lotus-position-medium-skin-tone" data-inline="false"></span>横尾忠則
                </el-button>
              </el-link>
              <el-button type="success" size="mini" plain round>#LINKIN PARK</el-button>
              <el-button type="success" size="mini" plain round>#GO!GO!7188</el-button>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="gap" timestamp="モラトリアム" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:alien-monster" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>「手に職を」と思い写真学校へ入学するが、画家への夢を諦めきれず、中退して美術系の予備校へ。</p>
            <p>制作に勤しむも、「アートは学ぶものか？」という思考のループから抜け出せず、一旦美術から距離を置くことに。</p>
            <p>地元宮崎に戻り、元々好きだった某コーヒーチェーンでバリスタ業務に精を出す。</p>
            <p>バリスタの腕が上がり、常連さんから「おいしい！」と言ってもらえるのが嬉しかったなぁ。</p>
            <p>休日は近くのライブハウスでロックを聴きまくっていました。</p>
            <div class="tag">

              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-link class="tag__link" type="success" :underline="false" target="_blank"
                href="https://youtu.be/LNxjL0wKvCc">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:youtube"
                    data-inline="false"></span>スーパーカー</el-button>
              </el-link>
              <el-button type="success" size="mini" plain round disabled>#basebment jaxx</el-button>
              <el-button type="success" size="mini" plain round disabled>#ポッドキャスト</el-button>

              <el-link class="tag__link" type="success" :underline="false" target="_blank"
                href="https://youtu.be/PsD0NpFSADM">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:youtube"
                    data-inline="false"></span>500日のサマー</el-button>
              </el-link>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="college" timestamp="大学" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:graduation-cap" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>とある一人旅がきっかけで英語を学びたくなり、地元の国際大学へ。</p>
            <p>授業が英語で行われるというユニークな環境で勉学に勤しむ。</p>
            <p>バリスタのバイトは卒業し、大学の夏休みや冬休みを利用して県外のホステルやキャンプ場にバイトに行っていた。</p>
            <img src="../static/otamu2.jpg" alt="">
            <small>愛猫と出会ったのもこの頃</small>
            <p>2013年には念願の留学！「昼からビールが飲みたい」「好きなバンドのギグに行きたい」という理由でイギリスを選択。そのバンドのチケットは、人気すぎてバルセロナまで遠征する羽目に。</p>
            <img src="../static/spain.jpg" alt="">
            <small>バルセロナで発見したオブジェ</small>

            <p>年末年始にはヨーロッパ一人旅を決行。トラブル続きだったが現地の人々の優しさに救われた。大学生活と合わせて、非常に濃い5年間でした。</p>
            <img src="../static/germany.jpg" alt="">
            <small>ドイツは人も食事も風景も最高でした</small>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-link href="https://youtu.be/c-wwK5QVv1Y" target="_blank" :underline="false" type="success">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:youtube"
                    data-inline="false"></span>Arctic Monkeys</el-button>
              </el-link>
              <el-link href="https://youtu.be/Vi76bxT7K6U" target="_blank" :underline="false" type="success">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:youtube"
                    data-inline="false"></span>Massive Attack</el-button>
              </el-link>
              <el-button type="success" size="mini" plain round disabled>#進撃の巨人</el-button>
              <el-link class="tag__link" type="success" :underline="false" target="_blank"
                href="https://www.youtube.com/watch?v=Yx0bZxSH7uI">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="logos:youtube"
                    data-inline="false"></span>恋する惑星</el-button>
              </el-link>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="tokyo" timestamp="上京" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:tokyo-tower" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>「一度は東京に行かなきゃダメだ」と繰り返していた父の教えが忘れられず、27にして遂に上京を果たす。</p>
            <p>同じ東京なのに、東西や路線ごとにカルチャーが栄えているのが面白いなと思い、古地図や地名に興味が湧きだしたのはこの頃。</p>
            <p>アートと英語、どちらも使える仕事に就き、大都会の大規模な展覧会に圧倒されるも、刺激的な日々を過ごす。一番印象に残っているのは<a class="text-link" target="_blank"
                href="https://www.fosterandpartners.com/">Foster + Partners展<span class="iconify"
                  data-icon="octicon:link-external-24" data-inline="false"></span></a></p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-button type="success" size="mini" plain round disabled>#バックミンスター・フラー</el-button>
              <el-button type="success" size="mini" plain round disabled>#まっちゃん</el-button>
              <el-button type="success" size="mini" plain round disabled>#佐藤雅彦</el-button>

              <el-link class="tag__link" type="success" :underline="false" target="_blank" href="http://www.haluta.jp/">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="twemoji:chair"
                    data-inline="false"></span>haluta</el-button>
              </el-link>
              <el-link class="tag__link" type="success" :underline="false" target="_blank" href="https://nug.jp/ja">
                <el-button type="success" size="mini" round><span class="iconify" data-icon="twemoji:classical-building"
                    data-inline="false"></span>nanzuka</el-button>
              </el-link>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="job-change" timestamp="はじめての転職" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:man-biking-medium-skin-tone" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <p>「もっとお客様と密にコミュニケーションをとりたい！」「別の東京らしさも体感したい」と考えるようになり、自転車メーカーの新事業部立ち上げスタッフの募集を見つけ、転職。</p>
            <img src="../static/ynk.jpg" alt="">
            <small>職場のあった台東区・谷中。穏やかでゆったりした街</small>
            <p>大学で学んだ英語、モラトリアム時代に磨いたバリスタスキル、生来の好奇心を存分に発揮。</p>
            <img src="../static/bike-tour.jpeg" alt="">
            <small>台湾の自転車工場へ見学に</small>

            <p>Myバイクも購入し、自転車通勤やポタリングの楽しさに目覚める。</p>
            <p>この頃担当した<a class="text-link" target="_blank" href="https://tokyobikerentals.com/jp/cityguide">自社メディア<span
                  class="iconify" data-icon="octicon:link-external-24"
                  data-inline="false"></span></a>の執筆やSNS運用がきっかけで、「創る」ことへの欲が再燃。</p>
            <p>友人のデザイナーやプログラマーの勧めもあり、WEB制作の勉強を始める。そしてハマる。</p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>このころの胸熱アイテム</h5>
              <el-button type="success" size="mini" plain round disabled>#ラジオ</el-button>
              <el-button type="success" size="mini" plain round disabled>#ピラティス</el-button>
              <el-button type="success" size="mini" plain round disabled>#筋膜リリース</el-button>
              <el-button type="success" size="mini" plain round disabled>#皇居周り</el-button>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

      <el-timeline-item id="current" timestamp="なう" placement="top" class="timeline">
        <el-row>
          <el-col :span="24" class="timeline__cover">
            <span class="iconify" data-icon="twemoji:woman-technologist-medium-skin-tone" data-inline="false"></span>
          </el-col>
          <el-col :span="24">
            <h2>もっといいものを作りたくて日々勉強中！</h2>
            <p>独学でHTMLやCSSを学び、現職へ。</p>
            <p>デザインからコーディング、ライティングまで一任してもらい、手探りながらも充実した日々を過ごす。</p>
            <p>一番好きなのは、アニメーションやエフェクトを加えたり既存ページのコードをより運用しやすく書き換えること。</p>
            <p>スマホ用ページの実装が主のため、もっと様々なプロジェクトに携わりたいと思い、転職活動中です！</p>
            <div class="tag">
              <h5><span class="iconify" data-icon="mdi-light:heart" data-inline="false"></span>最近の胸熱アイテム</h5>
              <el-button type="success" size="mini" plain round disabled>#WebGL</el-button>
              <el-button type="success" size="mini" plain round disabled>#イカとタコ</el-button>
              <el-button type="success" size="mini" plain round disabled>#一冊の本</el-button>
              <el-button type="success" size="mini" plain round disabled>#田中みな実のあったかタイム</el-button>
              <el-button type="success" size="mini" plain round disabled>#夜の永田町</el-button>
            </div>
          </el-col>
        </el-row>
      </el-timeline-item>

    </el-timeline>
  </div>
</template>
<style lang="scss" scoped>
  @import "@/assets/sass/_mixin";

  .timeline {
    padding-bottom: 8rem;

    &:nth-child(1) {
      margin-top: 0;
    }

    &__cover .iconify {
      display: block;
      margin: 0 auto 1.2rem;
      font-size: 4.8rem;
      filter: drop-shadow(0 2px 2px rgba(0, 0, 0, .2));

      @include mq(xl) {
        font-size: 6rem;
        margin-bottom: 2rem;
      }

    }

    p {
      padding-bottom: 1rem;
    }
  }

  .tag {
    color: #67C23A;
    background-color: #F0F9EB;
    padding: 1.2rem;
    margin-top: 1.6rem;

    .iconify {
      font-size: 2rem;
      vertical-align: text-bottom;
    }

    .el-button {
      padding: 0.6rem;
      margin: 0 4px 4px 0;

      .iconify {
        font-size: 1.2rem;
        vertical-align: text-top;
        margin-right: 0.4rem;
      }
    }
  }

  .text-link {
    color: #409EFF;

    &:hover {
      opacity: .6;
    }
  }

  small {
    display: block;
    font-size: 1rem;
    opacity: .6;
    margin-bottom: 4rem;
  }
</style>