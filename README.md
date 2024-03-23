<h1 align="center">ROtaiwan</h1>

<div align="center">
   <code>RAthena</code> <code>PandasWS</code> 基於ROenglishRE所改台灣繁體語系，可使用於RAthena及PandasWS身上
</div>

<br />

<div align="center">
  <!-- Clang Status -->
  <a href="https://github.com/xvn5002036/Rotaiwan/actions/workflows/build_servers_clang.yml">
    <img alt="Clang Status" src="https://img.shields.io/github/actions/workflow/status/xvn5002036/Rotaiwan/build_servers_clang.yml?label=clang&logo=llvm&style=flat-square">
  </a>
  <!-- GCC Status -->
  <a href="https://github.com/xvn5002036/Rotaiwan/actions/workflows/build_servers_gcc.yml">
    <img alt="Clang Status" src="https://img.shields.io/github/actions/workflow/status/xvn5002036/Rotaiwan/build_servers_gcc.yml?label=gcc&logo=gnu&style=flat-square">
  </a>
  <!-- MSBuild Status -->
  <a href="https://github.com/xvn5002036/Rotaiwan/actions/workflows/build_servers_msbuild.yml">
    <img alt="Clang Status" src="https://img.shields.io/github/actions/workflow/status/xvn5002036/Rotaiwan/build_servers_msbuild.yml?label=msbuild&logo=visualstudio&style=flat-square">
  </a>
  <!-- GitHub contributors -->
  <a href="https://github.com/xvn5002036/Rotaiwan/graphs/contributors">
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/xvn5002036/Rotaiwan?style=flat-square">
  </a>
  <!-- GitHub license -->
  <a href="https://github.com/xvn5002036/Rotaiwan/blob/master/LICENSE">
    <img alt="GitHub license" src="https://img.shields.io/github/license/PandasWS/Pandas?style=flat-square">
  </a>
  <!-- Discord Online -->
  <a href="https://discord.gg/pjvMUtZ7Ae">
    <img alt="Discord Online" src="https://img.shields.io/discord/1130860241223946300?color=6A7EC2&label=Discord&logo=discord&logoColor=ffffff&style=flat-square">
  </a>
</div>

<div align="center">
  <h3>
    <a href="https://XXXXXXX" target="_blank">
      官網(未定案)
    </a>
    <span> | </span>
    <a href="https://rotaiwan.gitbook.io/ro-taiwan-de-shi-jie/" target="_blank">
      使用手册
    </a>
    <span> | </span>
    <a href="https://github.com/xvn5002036/ROtaiwan/releases">
      下載
    </a>
    <span> | </span>
    <a href="https://github.com/xvn5002036/ROtaiwan/graphs/contributors">
      貢獻人
    </a>
    <span> | </span>
    <a href="https://discord.gg/pjvMUtZ7Ae" target="_blank">
      Discord
    </a>
  </h3>
</div>

<div align="center">
  <sub>
  如果你覺得這裡對你有幫助，請點右上角的星星 ★Star 給他一顆星星
  <br />
  Craft with ❤︎ by
  <a href="https://github.com/llchrisll/ROenglishRE">ROenglishRE</a>
  </sub>
</div>

## 目錄

-   [準備項目](#準備項目)
-   [ROtaiwan說明](#ROtaiwan說明)


## 準備項目

1.請使用RO韓國版主程式：https://ro.industrial-illusions.net/files/

(下載完主程式請更新)

2.下載NEMO程式 位登入器添加補丁(Diff)

下載位置：http://nemo.herc.ws/


## ROtaiwan說明

@已脫殼沒使用NEMO
2021-11-17_RagexeRE.exe

@是改登入器的必備文件(已設定好)
NEMO/2023.log
NEMO/2023_inputs.db

@不會用NEMO去形成Diff捨直接執行(已製作完成)


MyRagnarok 2024.exe  是2021-11-17_RagexeRE.exe轉換過來的



以下要用20220406版本需要編譯

在src\custom\defines_pre.hpp下貼上 #define PACKETVER 20220406

以下所示 在進行編譯

```
#ifndef PACKETVER
	/// Do NOT edit this line! To set your client version, please do this instead:
	/// In Windows: Add this line in your src\custom\defines_pre.hpp file: #define PACKETVER YYYYMMDD
	/// In Linux: The same as above or run the following command: ./configure --enable-packetver=YYYYMMDD
	#define PACKETVER 20220406
#endif
```



