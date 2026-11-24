# Random News

**One link that sends you to a different news site every time you open it.**

Most of us read the same one or two news outlets every day, and our picture of the world narrows to match. Random News is a tiny tool for breaking that habit: open the link, and it redirects you to a randomly chosen news site from a list of outlets in the US and abroad. Open it again and you will probably land somewhere else.

The goal is a more balanced view of the world through a more varied news diet.

## Try it

**<https://mrkiwisir.github.io/Random-News/>**

Ways to use it:

- **Set it as your browser homepage or new-tab page** so every session starts at a different outlet.
- **Bookmark it** and use that bookmark in place of your usual news site.
- **Add it to your phone's home screen** as a "news roulette" button.

## Sources in the rotation

| Outlet | Based in |
| --- | --- |
| [ABC News](https://abcnews.go.com/) | United States |
| [Al Jazeera](https://www.aljazeera.com/) | Qatar |
| [AP News](https://apnews.com/) | United States |
| [Axios](https://www.axios.com) | United States |
| [CBS News](https://www.cbsnews.com/) | United States |
| [CNN](https://www.cnn.com/) | United States |
| [Drudge Report](https://drudgereport.com/) | United States |
| [Euronews](https://www.euronews.com/) | France |
| [France 24](https://www.france24.com/en/) | France |
| [The Guardian (international edition)](https://www.theguardian.com/international) | United Kingdom |
| [HuffPost](https://www.huffpost.com/news/) | United States |
| [NBC News](https://www.nbcnews.com/) | United States |
| [NPR](https://www.npr.org/) | United States |
| [PBS NewsHour](https://www.pbs.org/newshour) | United States |
| [Politico](https://www.politico.com/) | United States |
| [Reuters](https://www.reuters.com/) | United Kingdom |
| [TIME](https://www.time.com/) | United States |
| [USA Today](https://www.usatoday.com/news/) | United States |
| [Vox](https://www.vox.com/) | United States |

Inclusion in the list is not an endorsement of any outlet. The point is variety: you decide what to make of what you read.

## How it works

The whole project is one file, [`index.html`](index.html), with a few lines of JavaScript:

1. It holds a list of news site URLs.
2. On page load it picks one at random.
3. It adds a timestamp to the address so your browser does not reuse a cached redirect.
4. It sends you there.

There is no server, no account, no tracking, and no build step. The page is hosted for free on GitHub Pages.

## Make your own version

Want different outlets, a different language, or a list for a topic other than news (science, local papers, sports)?

1. **Fork** this repository.
2. Open `index.html` and edit the `sites` list. Use full addresses that start with `https://`.
3. In your fork, go to **Settings → Pages** and publish from the `main` branch.
4. Your version will be live at `https://<your-username>.github.io/Random-News/`.

Tip: list a site more than once to make it come up more often.

## Contributing

Suggestions for outlets to add are welcome, especially ones that widen the range of countries and viewpoints. Open an issue or a pull request.

## License

[Mozilla Public License 2.0](LICENSE)

---

*Keywords: random news site, random news generator, news redirect, news roulette, balanced news sources, diversify your news, escape the filter bubble, media diet, browser homepage for news.*
