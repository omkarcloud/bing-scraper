![Bing Scraper Featured Image](https://raw.githubusercontent.com/omkarcloud/bing-scraper/master/images/bing-scraper-featured-image.png)

<div align="center" style="margin-top: 0;">
  <h1>✨ Bing Scraper 🚀</h1>
  <p>💦 Bing Scraper helps you collect search results from Bing. 💦</p>
</div>
<em>
  <h5 align="center">(Programming Language - Python 3)</h5>
</em>
<p align="center">
  <a href="#">
    <img alt="bing-scraper forks" src="https://img.shields.io/github/forks/omkarcloud/bing-scraper?style=for-the-badge" />
  </a>
  <a href="#">
    <img alt="Repo stars" src="https://img.shields.io/github/stars/omkarcloud/bing-scraper?style=for-the-badge&color=yellow" />
  </a>
  <a href="#">
    <img alt="bing-scraper License" src="https://img.shields.io/github/license/omkarcloud/bing-scraper?color=orange&style=for-the-badge" />
  </a>
  <a href="https://github.com/omkarcloud/bing-scraper/issues">
    <img alt="issues" src="https://img.shields.io/github/issues/omkarcloud/bing-scraper?color=purple&style=for-the-badge" />
  </a>
</p>
<p align="center">
  <img src="https://views.whatilearened.today/views/github/omkarcloud/bing-scraper.svg" width="80px" height="28px" alt="View" />
</p>

<p align="center">
  <a href="https://gitpod.io/#https://github.com/omkarcloud/bing-scraper">
    <img alt="Open in Gitpod" src="https://gitpod.io/button/open-in-gitpod.svg" />
  </a>
</p>
  
---

## 👉 Explore Our Other Awesome Products

- ✅ [Botasaurus](https://github.com/omkarcloud/botasaurus): The All-in-One Web Scraping Framework with Anti-Detection, Parallelization, Asynchronous, and Caching Superpowers.

---

Bing Scraper helps you collect search results from Bing.

## 🚀 Getting Started

1️⃣ **Clone the Magic 🧙‍♀:**
```shell
git clone https://github.com/omkarcloud/bing-scraper
cd bing-scraper
```
2️⃣ **Install Dependencies 📦:**
```shell
python -m pip install -r requirements.txt
```
3️⃣ **Let the Scraping Begin 😎**:
```shell
python main.py
```

Find your data in the `output` directory.

![Bing Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/bing-scraper/master/images/bing-scraper-csv-result.png)

*Note: If you don't have Python installed. Follow this Simple FAQ [here](https://github.com/omkarcloud/bing-scraper/blob/master/advanced.md#-i-dont-have-python-installed-how-can-i-run-the-scraper) and you will have your Bing data in next 5 Minutes*

## 🤔 FAQs

### ❓ How to Scrape Bing?

1. Open the `main.py` file.
2. Update the `queries` list with the locations you are interested in. For example:

```python
queries = [
  "Mango",
  "Watermelon",
]

Bing.search(queries, max=10)
```

3. Run it.

```bash
python main.py
```

Then find your data in the `output` directory.

### ❓ How to Scrape More Bing Search Results Using Your Bing API?

To scrape additional data, follow these steps to use our Bing API. You can make 50 requests for free:

1. Sign up on RapidAPI by visiting [this link](https://rapidapi.com/auth/sign-up).

![Sign Up on RapidAPI](https://raw.githubusercontent.com/omkarcloud/assets/master/images/sign-up.png)

2. Then, subscribe to our Free Plan by visiting [this link](https://rapidapi.com/Chetan11dev/api/bing-scraper/pricing).

![Subscribe to Free Plan](https://raw.githubusercontent.com/omkarcloud/assets/master/images/free-subscription.png)

3. Now, copy the API key.

![Copy the API Key](https://raw.githubusercontent.com/omkarcloud/assets/master/images/api-key.png) 

4. Use it in the scraper as follows:
```python
Bing.search("Orange", max=10, key="YOUR_API_KEY")
```

5. Run the script, and you'll find your data in the `output` folder.
```bash
python main.py
```   

The first 50 requests are free. After that, you can upgrade to the Pro Plan, which will get you 1000 requests for just $9.

### ❓ How did you build it?

We used Botasaurus, It's an All-in-One Web Scraping Framework with Anti-Detection, Parallelization, Asynchronous, and Caching Superpowers.

Botasaurus helped us cut down the development time by 50% and helped us focus only on the core extraction logic of the scraper.

If you are a Web Scraper, you should learn about Botasaurus [here](https://github.com/omkarcloud/botasaurus), because Botasaurus will save you countless hours in your life as a Web Scraper.

<p align="center">
  <a href="https://github.com/omkarcloud/botasaurus">
  <img src="https://raw.githubusercontent.com/omkarcloud/assets/master/images/mascot.png" alt="botasaurus" />
</a>
</p>


### ❓ Need More Help or Have Additional Questions?

For further help, contact us on WhatsApp. We'll be happy to help you out.

[![Contact Us on WhatsApp about Bing Scraper](https://raw.githubusercontent.com/omkarcloud/assets/master/images/whatsapp-us.png)](https://api.whatsapp.com/send?phone=918295042963&text=Hi,%20I%20would%20like%20to%20learn%20more%20about%20your%20products.)

## Love It? [Star It! ⭐](https://github.com/omkarcloud/bing-scraper/stargazers)

## Made with ❤️ using [Botasaurus Web Scraping Framework](https://github.com/omkarcloud/botasaurus)