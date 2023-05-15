# Rust
<br>
Create Repositories : 2023/05.15
<br><br>

Rust install : https://www.rust-lang.org/ja/tools/install
<br>
Windows Subsystem for linux :<br>
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
<br><br><br>

# Cargoのプロジェクトを作成する流れ

• cargo new を使ってプロジェクトを作成できる
• cargo build を使ってプロジェクトをビルドできる
• cargo run を使うとプロジェクトのビルドと実行を 1 ステップで行える
• cargo check を使うとバイナリを生成せずにプロジェクトをビルドして、エラーがないか確認
できる
• Cargo は、ビルドの成果物をコードと同じディレクトリに保存するのではなく、target/debugディレクトリに格納する
<br>
〇 リリースに向けたビルド
プロジェクトが最終的にリリースできるようになったら、cargo build --release を使い、最適化した状態でコンパイルできます。
このコマンドは実行ファイルを、target/debug ではなく、target/release に作成します。