# Rust 이미지를 기반으로 빌드
FROM rust:1.72

# 작업 디렉토리 설정
WORKDIR /app

# `Cargo.toml` 및 `src` 복사
COPY . .

# 종속성 설치 및 빌드
RUN cargo build --release

# 실행 명령
CMD ["./target/release/backend"]



