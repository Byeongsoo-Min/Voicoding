# π€ Voicoding(λͺ©μλ¦¬λ‘ μ½λ©νκΈ°)
**λ μμ§λ μ½λ©μ μμΌλ‘ νλ?**

**μ΄μ€λ½κ² λκ° μμΌλ‘ μ½λ©ν΄?**

**μμ¦μ λ€ λͺ©μλ¦¬λ‘ ν΄π**

## About


**Voicoding**μ μΉνμ΄μ§μμ μ¬μ©μμ μμ±μ Python μ½λλ‘ λ³ννκ³ , μ€νμμΌμ£Όλ νλ‘μ νΈμλλ€. λΉμ μ μλ¦λ€μ΄ λͺ©μλ¦¬λ‘ μνλ μ½λλ₯Ό μ§λ³΄μΈμ!

## API & Open source
* **[Google Speech-to-Text](https://cloud.google.com/speech-to-text)**
* **[mattdiamond/Recorderjs](https://github.com/mattdiamond/Recorderjs)**
* **[Google Fonts](https://fonts.google.com)**
* **[Font awesome](https://fontawesome.com)**
* **[judge0/ide](https://github.com/judge0/ide)**


## How to Use
1. **[Google Cloud Platform](https://cloud.google.com)** μ νλ‘μ νΈλ₯Ό μμ±ν ν, **Speech-to-Text**μ μλΉμ€ κ³μ μ λ§λ λ€.
2. μλΉμ€ κ³μ μ μλΉμ€ κ³μ  ν€(JSON)μ λ€μ΄λ°κ³ , μμ€ν νκ²½ λ³μμ κ³μ  ν€ κ²½λ‘λ₯Ό **GOOGLE_APPLICATION_CREDENTIALS**λ‘ μ μ₯νλ€.

	 * μ§μ  pathμ μλ ₯
	 * Linux/macOS
		`export GOOGLE_APPLICATION_CREDENTIALS="KEY_PATH"`
	 * Windows
		 `$env:GOOGLE_APPLICATION_CREDENTIALS="KEY_PATH"`

3. νλ‘μ νΈλ₯Ό Cloneνλ€. 
`git clone http://khuhub.khu.ac.kr/2019102168/Voicoding.git`

4. Installation
    * `npm install`
5. domain, port λ±μ λ³κ²½ν ν μ€ννλ€.


## Usage
Voicodingμ μλ ₯λλ μμ°μ΄κ° PythonμΌλ‘ λ²μ­λλ μμ€μλλ€. μ΄λ κΈ°ν λ€λ₯Έ μΈμ΄ [c++, C, JavaScript λ±..]μΌλ‘ λ²μ­λκ² μμ νμ€ μ μμ΅λλ€. js/ide.js μμ parseInt(), resolveLanguageId(), resolveApiUrl() μ ν΄λΉνλ νλΌλ―Έν°λ₯Ό μλμμ μ°Ύμ λ°κΏμ£ΌμΈμ. μ΄ν, Voicoding.js μμ νμ΄μ¬ λͺ¨λΈλ‘ μ€μ λμ΄ μλ κ°λ€μ ν΄λΉ μΈμ΄μ λ§κ² λ€μ λͺ¨λΈλ§ ν΄μ£ΌμΈμ.

	"45" Assembly (NASM 2.14.02)   
	"46" Bash (5.0.0)  
	"47" Basic (FBC 1.07.1)   
	"1011" Bosque (latest)    
	"75" C (Clang 7.0.1)  
	"1013" C (Clang 9.0.1)  
	"1001" C (Clang 10.0.1)  
	"48" C (GCC 7.4.0)  
	"49" C (GCC 8.3.0)  
	"50" C (GCC 9.2.0)  
	"51" C# (Mono 6.6.0.161)  
	"1022" C# (Mono 6.10.0.104)  
	"1021" C# (.NET Core SDK 3.1.302)  
	"1023" C# Test (.NET Core SDK 3.1.302, NUnit 3.12.0)  
	"76" C++ (Clang 7.0.1)  
	"1014" C++ (Clang 9.0.1)  
	"1002" C++ (Clang 10.0.1)  
	"52" C++ (GCC 7.4.0)  
	"53" C++ (GCC 8.3.0)  
	"54" C++ (GCC 9.2.0)  
	"1015" C++ Test (Clang 10.0.1, Google Test 1.8.1)  
	"1012" C++ Test (GCC 8.4.0, Google Test 1.8.1)  
	"1003" C3 (latest)   
	"86" Clojure (1.10.1)  
	"77" COBOL (GnuCOBOL 2.2)   
	"55" Common Lisp (SBCL 2.0.0)   
	"56" D (DMD 2.089.1)   
	"57" Elixir (1.9.4)   
	"58" Erlang (OTP 22.2)   
	"44" Executable  
	"87" F# (.NET Core SDK 3.1.202)  
	"1024" F# (.NET Core SDK 3.1.302)  
	"59" Fortran (GFortran 9.2.0)   
	"60" Go (1.13.5)  
	"88" Groovy (3.0.3)   
	"61" Haskell (GHC 8.8.1)   
	"62" Java (OpenJDK 13.0.1)  
	"1004" Java (OpenJDK 14.0.1)  
	"1005" Java Test (OpenJDK 14.0.1, JUnit Platform Console Standalone 1.6.2)  
	"63"  JavaScript (Node.js 12.14.0)  
	"78"  Kotlin (1.3.70)  
	"64" Lua (5.3.5)  
	"1006" MPI (OpenRTE 3.1.3) with C (GCC 8.3.0)  
	"1007" MPI (OpenRTE 3.1.3) with C++ (GCC 8.3.0)  
	"1008" MPI (OpenRTE 3.1.3) with Python (3.7.3)  
	"1009"Nim (stable)   
	"79" Objective-C (Clang 7.0.1)  
	"65" OCaml (4.09.0)  
	"66" Octave (5.1.0)  
	"67" Pascal (FPC 3.0.4)  
	"85" Perl (5.28.1)  
	"68" PHP (7.4.1)  
	"43" Plain Text  
	"69"  Prolog (GNU Prolog 1.4.5)   
	"70" Python (2.7.17)  
	"71" Python (3.8.1)  
	"1010" Python for ML (3.7.3)  
	"80" R (4.0.0)  
	"72" Ruby (2.7.0)  
	"73" Rust (1.40.0)  
	"81" Scala (2.13.2)  
	"82" SQL (SQLite 3.27.2)  
	"83" Swift (5.2.3)  
	"74" TypeScript (3.7.4)  
	"84" Visual Basic.Net (vbnc 0.0.0.5943)   
## Author
* λ―Όλ³μ(Min byeong-soo)

	:email: : qud9783@khu.ac.kr
* μ²νμ°(Chon hyun-woo)

	:email: : 2019102233@khu.ac.kr


## License
Voicoding is licensed under the GNU General Public License v3.0.
