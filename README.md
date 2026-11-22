# Codeforces Solutions

My solutions to [Codeforces](https://codeforces.com/) problems, written in C++17.

- **Handle:** [async_thread](https://codeforces.com/profile/async_thread)
- **Language:** C++17
- **Author:** Yassine Abbou, final-year software engineering student at ENIAD Berkane

## Structure

One folder per contest ID, one file per problem: `<contest>/<letter>_<title>.cpp`.

```
codeforces-solutions/
├── README.md
├── .gitignore
├── 1850/
│   ├── A_to_my_critics.cpp
│   └── B_ten_words_of_wisdom.cpp
└── 2290/
    └── D_letters_down.cpp
```

Only accepted solutions are added. Each file starts with a short header: problem title, link, tags, idea and time complexity.

## Solutions

| Problem | Tags | Solution |
|---------|------|----------|
| [1850A – To My Critics](https://codeforces.com/problemset/problem/1850/A) | implementation | [A_to_my_critics.cpp](1850/A_to_my_critics.cpp) |
| [1850B – Ten Words of Wisdom](https://codeforces.com/problemset/problem/1850/B) | implementation, sortings | [B_ten_words_of_wisdom.cpp](1850/B_ten_words_of_wisdom.cpp) |
| [2290D – Letters Down](https://codeforces.com/problemset/problem/2290/D) | data structures, dsu, greedy, implementation, strings | [D_letters_down.cpp](2290/D_letters_down.cpp) |

## How to compile and run

```bash
g++ -std=c++17 -O2 -o solution 1850/A_to_my_critics.cpp
./solution
```

On Windows (MinGW):

```bash
g++ -std=c++17 -O2 -o solution.exe 1850\A_to_my_critics.cpp
solution.exe
```

## Contact

- GitHub: [async-thread](https://github.com/async-thread)
- Email: yassineabbou@proton.me
