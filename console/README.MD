windows https://download.oracle.com/graalvm/23/latest/graalvm-jdk-23_windows-x64_bin.zip
https://github.com/upx/upx/releases/tag/v4.2.4

run:
    maven install -Pnative
    upx-4.2.4-win64\upx.exe -k my-app.exe
