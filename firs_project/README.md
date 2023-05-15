started : 2023/05/15<br><br>

公式ドキュメント : https://doc.rust-jp.rs/book-ja-pdf/book.pdf<br>
いつも通り公式ドキュメントに沿って進めていく。


# Cargoのプロジェクトを作成する流れ

• cargo new を使ってプロジェクトを作成できる
• cargo build を使ってプロジェクトをビルドできる
• cargo run を使うとプロジェクトのビルドと実行を 1 ステップで行える
• cargo check を使うとバイナリを生成せずにプロジェクトをビルドして、エラーがないか確認
できる
• Cargo は、ビルドの成果物をコードと同じディレクトリに保存するのではなく、target/debugディレクトリに格納する
