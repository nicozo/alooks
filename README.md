# エペスク
# サービス概要
### 3行で
ApexLegendsで新しいプレイヤーと交流したいが、なかなか募集に入れずにいるプレイヤーに  
気軽に目当てのスクワッドを見つけることができる  
スクワッド募集掲示板サービスです  
### メインターゲットのユーザー
Twitterでの募集に不安を抱いているApexLegendsプレイヤー  
新しいプレイヤーと気軽に交流したいApexLegendsプレイヤー  
### ユーザーが抱える課題
募集主や参加希望者のTwitterアカウントの「フォロワーが少ない」「メディア欄が少ないまたは投稿していない」「ツイートが少ない」といった要素から人物像やレベル感がイメージしづらいことが多々ある  
抽象的な募集が多いため、募集主と参加者でミスマッチが発生する  
募集とは無関係なツイートなどにより、TLで募集ツイートが埋もれてしまいスクワッドを集めるのに複数回ツイートする必要がある  
晒し合いが多いTwitterでの募集は勇気がいる  
強さを測りたい場合、いちいち相手のメディア欄を遡り戦績やクリップを確認する必要がある  
募集された人数に達しているにも関わらずツイートが残っており、募集の有無がわかりづらい  
### 解決方法
プロフィールに簡単な戦績やプレイスタイル等を掲載することで相手のレベル感や楽しみ方の方向性ががなんとなくわかる  
募集内容を具体化することで、参加者と募集主のミスマッチを防ぐ  
プレイ後スクワッドに対し、第３者からの簡単なフィードバックをもらうことで人物像をわかりやすいものにする  
投稿に現在のスクワッド人数を表示することで参加の可不可を明確化させる  
### 実装予定の機能
#### ゲストユーザー
掲示板の閲覧  
#### ログインユーザー
掲示板CRUD  
ユーザーCRUD  
ログイン機能  
ApexLegends戦績表示機能  
プロフィール機能  
検索機能  
#### 管理者ユーザー
ユーザーCRUD  
掲示板CRUD  
### 今後実装したい機能
Twitterアカウント連携  
フィードバック機能  
参加リクエスト通知機能  
### なぜこのサービスを作りたいのか
ApexLegendsを通してたくさんの人と遊ぶ楽しさを味わってほしいからです。  
Twitter募集では「#apex募集」というハッシュタグをつけてスクワッドの募集を行うことが一般的です。  
多くのプレイヤーがそのハッシュタグを使っていることから、金銭を目的とした代行業者の無関係なツイートなどがTLに混在しています。  
募集対象者も「強い人」などの抽象的な表記が多く、募集主の基準になるので期待値以下のプレイヤーだった場合、後日晒されてしまうといったことも少なくありません。  
またツイート数やメディア欄が少ないアカウンもあり、人柄が予想できず私自身Twitterでの募集に後ろめたさを感じています。  
実際に私のフレンドも同様の意見を持つ方がいます。  
そんな人のためにミスマッチを防ぎ分かりやすいApexLegends専用の募集掲示板を作ろうと思いました。  
ユーザーにとってゲームするフレンドがいない時の拠り所になればいいなと思っています。  
### 画面遷移図
[画面線遷移図](https://www.figma.com/file/e7kNIMUHonHBqazTmlwWQQ/Apex-Looks?node-id=18%3A186)

### ER図
[ER図](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=ApexLegendsPortfolio#R7V1tk6K4Gv01VPX90F0givCxtbtn7k7P3amevbU794uVlqjUIDiA3fb8%2BhuEoJKIQXkzSdXUbhMwYp6THHKeFxR9vNx8CsBq8dW3oav0VHuj6A9Kr6f1ewb6X9zykbSYqpY0zAPHTi%2FaNXx3fsO0UU1b144Nw4MLI993I2d12Dj1PQ9Oo4M2EAT%2B%2B%2BFlM989%2FNYVmEOi4fsUuGTr344dLdJWY9DfnfgMnfkCf7VmWMmZJcBXpz8lXADbfz9ogpvoyfei9B6%2FwWAJPOhF6MxXEPyEgTJ4XERR%2FFPvld4T%2BjeLr76b%2B%2F7chWDlhHdTf4mapyG65GkGlo4bj%2FNeR6O0I%2FR1%2BqOijwPfj5K%2FlpsxdGNjYTsk9%2FR05Gw2EEHcL8MH%2Fv7fl97o06%2FZ5j%2B3Lw%2Bj70NgrKxbbZB08wbcdTrC6xAGYTpC0QcedzRYq%2FjPCLzGTaMwAkGUwkNXUQMyeAQcD%2F00%2FUHbHrsuWIXO9vKkZeG49jP48NcR7ggfjWbOBtovCTriaxFQnlFn8WHceTzM39ObiU8D15l76O8p%2Bu3xN44CGKJ7eQZhlF5Bjk46YG8wiOBmrykdrU%2FQX8Io%2BECX4LMYFelU0Qfp8fsOeD3cttjDnN5PG0EKpHnW984%2B6I%2FURGXMZRDmKrbUSwzw0cIPnN%2Bxfdx0PPettz1%2Bd5YuQuhnCOxc08jfLhVbKziuO%2FZdPzax53uQsHJ8kR34q79AMIdR2rDynXRGDUboHxqasXo3UAboXsfoWNsdo3%2Fx5UE09r0wChCa4j4gMuo7jA07ivxV2qkLZ7j%2FIB34%2BO9XP4rQBDwGgeIpcBoYGAisOKgNBkMCBt%2B%2BHAUCGoHIAe4LWo6BN3cTs21XZ7AzG8W21NHORjg%2F9Pkp6qPxnLnb9XXh2Db0SljEYLbIngn0khZIO9sNS%2BnegIsWHw9EaI6sPTskzJrd5wWWNglL%2F9dzfq3hvx9atjdegpNrR%2BEKTB1v%2Fpx80sgBYtAYIDbHp2ivUoAwddcEQixJCUyUoNZJCUbblIDRyAKDZhYIaDu4v0v5wGI2B%2B98kD3F7szsgSW8QXMDrb7x9Omp3jru8z7eXQE3hP%2FqOlE0gwzhiAEvAJIY2iQGq3Vi0Pklhgzikhh6fcLMcAkcV1RmKAEN8ZiBFP0kMzTODJm82B41lFATr44a2O3BPTWQamEI3dkETYzAt9fTyPG9GzRIEdd8wI4H8fiAFBklHzTPB8zupdr4oISUeHV8YDLbg3c%2BwF%2B5Z2YbfeHEn01enSBa3MQzRLj9Ajs%2BhOMHnRQdJT80zw9m2%2Fygl1AUr40fdPbwEO75gVQMQ7i5gd56mdCCiPxQAh%2Fi8QOpPUp%2BaJwfshDN9vihhK54dfzQZ7YH9%2FxAyobgDaC5G28cuOYAdgwIxwH9Em5GyQG1cUC%2FbQ7ol3gWuDYOyDAuOaBPUv0cLOHEsRMSeOwpaLs6GimPhnL%2FoNzryqOp3BuK%2BaQ8DhRzrFiG8qgrpqZY1vYPdP0obTGTT%2FUVa7z9lKmYjxyzSglUCccqOum6kqzSPKsM22YVvYSH6tpYJcO4ZBWddEA54cRfQW8SwKkf2Devvu9C4CXykw1nYO1GiQIVBWu%2BBSh2mAhHE%2FipV9JEmzShq23TRL%2BEo%2BraaCLDuKSJPumHmgYfqwjakxUIw%2FeYKJKwV54JoQQghCOEAfkgEfj%2BUqa1ozMD7CfAyzYtRcGi2DEzbuXrtiH5u3L%2BzqbARWntNBzURt8GSd88pbUbZzG4UekCzdJbA%2BuzQTK4gGntJQCxOTTf%2FhSt9hGvK894hvQnsVFCiUon5SmBhrdmKYF0Jz3xRAlneZT4pAR6JaoJ%2BpBAjFDaFyQQI8jaVx3YJLBuFutjhBIuwWvT%2BIyzCl%2FxSQekxy9yIlfYSicloCEcM5gyP6UDzEDNZ2%2BUGkxSVeCGGkx2nZd3ajBJaWC6DuLxm4S%2F1sCeLOHyFXIfjVwCEcIxAl52JCO0ygi0jPZGGcHiOCAgw7hkBIskfiec2AGYRQURY9zvGUogRDiGMGXOYhcYgpbT3uyegeOcRfOsnEUuGcKk5CyuVq4zBXH1q4mNZqvrePAmLoQSOUuuaaEELISjBY1ScJ%2BAArTnEDt80Bq78Oe%2BB9zHXWviEkpIQevFtBEt3XQ%2BQ8%2B%2Bj9%2BDgw4fX37DwP%2FL%2Fwq8D0wlu3NL4Nl%2FbqETxD8XYjpBxg0%2B%2Ftk%2F%2BBEf3A3w4cNm%2F%2BQD5hy4caJ%2Fdleiox97Z3Yfig%2FwZ9C%2B%2Bm37xYWxZ6G%2FDqawaFTTRTbCbHb0QhzaGQ8x64KlqRTsZI0BdNEcf4MHd1wA0G%2F%2BtrxFFi2Hc19wLkw%2BCC758emndoAkOhrm3iaj4UHBHSWDQ3RUGbIpFeLjJfBDBkUqZFAkbcWjwsyo68FEo5R6l0%2BolyY19Ni3RAVRkTQk1PeyH2x3TsMitRKzlffHVI1SrV3AwMgykDj%2BiKr1K4UIU3dNYISS%2FiKJoXliYH1EqI8YKDVXnr5oR7FwfcyQIV0yg0YprCJefGQZRIhHDJR3gEhiuDBm%2FgxioIVINrxjIEXtpy9t69qVbhmksr0bC1LajnNdBSOGEogQkBhkGaUu7BioEZINMwPHhZR2MJesoFHe5fGKpqSo4fNlsCEeP1DKZRBYaNfpeeCI3HlAd07PH%2FvnTnpAh%2BwuUBJgrF5PPKqnvZ6YFzrj9dRUDE3sBdFysGR1e2parqdevqe6%2FZ4smeTX7dHX9sGcefdr9ehjo57EttE1aA9zDv3%2Bucg2hyemSHXAfv7j84s7XJpWGK7ePj1HP8Pnx1vSPTyD0H4F05%2FSox%2BvM8aheYaUIqYaLdRQq%2BLpm2qxHmGxYkPJXdg%2BAgonwSXufCoKagMByUZX6swvhLhQOzDqSJBaPN%2BO%2FAvhULDpqjbSlKm7BvAh38F9ia%2BmGjKgoa1RMiCl%2ByutblQIcUkGpP7Ote%2F%2BQjQIxwXy%2FdvtbwwoXvtmuYBBg70Cz0whviURYI0o75ZB48JLsYoLESDc4q%2BRDwfbV2klbzyRWh46M8CFJPBzOyVtOEslrjw9h241ydnVcza7j7ZAzaPhoDbS1kjW5knO0yRzZ1IWydwCCnolAFFA5NW%2BdISpuyYQIhM2q5f0SlMCDW%2BNUgK2eo4SxtcagV2MdUkMlJRN8cS9ahI2OeUFmZbTga0CTd9rlhf4qDRVDHFJB5R0nHg%2B91S963TQjP3FW%2F5l8k0Hln9a7k3D6z8fqTfFGJfrPyXxJln%2F%2Bzyv%2F5Vk1%2FC5%2Fuvdzz%2BgVgbEWQX0PIJjOTjZuSM5CzVWFCyKA%2BhM%2BoGRS4cxrBwimesJ5joa5DuqLv3gwQCvlqGPB89%2FDp%2FA9OMD%2FqHe4pmUf8XyZIXGZ%2BYHy%2BKHHOVaHJfEkkYB7NFVzsoVfcySn07WFaziMYRuN6lSl30cPQGBgulRxnFZWyY4%2Ff7oKvWV6NNnWYT%2FB1L67xahpGCVgOA5%2F5s%2BEFKg7gAlNFlPkH5%2FtKpR11NO8CyT9AXlBAFqRlWJB%2BEoYSDDGztACU1WEqTDgBQzrymM5RyTJMgXjxLwbeyZGis5wtPCMUwIRwuUitNS7tvTZHM1R1hjETNxufIFnFI1WvJ4cUzqOQtEMi%2FKqH21%2BZ7p90du7ThX%2B%2Fqnd3bVppM1n01G%2F93kzk6qfUWA2ByfooNqOZyluyYQIuORmtjanaCEJtMU6Pd3veFIZ5ljKCgfkDt4Dywhp3WAq0SGcMQwIB8dCCRUF6i0C0a6jiqpuQii88KW8Kq%2FH7Z0rmOi5gLA%2BeqmZg6Q7AWA829QzfdUc6DSgOF5p0VYH1a2xli9U7V9vN6qd6oxLIRsfPANBg4arq2icjhlygXpnYf4wqfN04g%2FIoU3hng9h1NClGFGfH%2FYLMINMqQrriCy9G14lMoFUuW0Xu7lvj2citWeLmf0Ti9KchNWBgMFM6O7uhylNj3nulwCfPH2YYYI9YCrBIRw2y9DVgRuQpc7QQmt63IGwy6cI10uQb2AfEDuSqUux4QM8YiBVOqTTCu5ydvBwcqFXuiU1700nGlllKjoKwn9%2FHXiSHBWVzKtMBAF2uNZJzmdyxDKIanDyT1eESCEi58cStmvA5TQeqbVkJT9eM%2B0Gp7W%2FfjkBFL3k5lWBXgQjxKk7NcBSmg902pIexVY28pfzZRwWvrjkxLoL%2FyIlRxJC8Win0C0wBCeK4PxLgvGS5fck6FJDM%2ButYYmmbnX3wz6OTyyRiZZ1mFH%2FXx8S82BSkMGRbQToD4Ml9O6CepCheEkqI%2F5QZuLt1NzYMy%2Fq4k93i5XCk%2FvNQtrPKsIB00AvJ%2FoP5H00MSLTy6%2B0lAZn7nr89BYshZeE3sv60hob1c8NBapynLuobEErYVnyVp45QAh3L7LkgUTOkAJrXtoLPFq4VmC1sKzZC28UngQjxJkwYQOUELrHhqLVGR599BYp4sm8EkJpE6ZSTmSF4rrJYjDC5kSSoNJMUOIofhpvVxQdp8SlN1w4q2mSs2Pjc0vy7xNLVhG9Gs2z0pThVP9UuwX8jmXyVaaKnW%2FkpAQLstKU6Xy18Q27xQxtJ6Aq6nX%2B6Lm8wwiaKlUTSWVP5mDy4YNAemh22XEeIhdwr63k7FLRzmkteAlw7TucBhB6filrLYeju%2FTyc5qDmHSVBlvWne8KVawT8KbwRNXb7xpTrYZ4hfElY43zb%2Bj1sx1dDaq0WHg%2B9H%2B5QFYLb76Noyv%2BD8%3D)
### スケジュール
企画〜技術調査：4/2〆切  
README〜ER図作成：4/10 〆切  
メイン機能実装：4月中旬 - 8月中旬  
β版をリリース（MVP）：8月末〆切  
本番リリース： 9月中旬  
