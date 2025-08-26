# handwritten-to-json
An small example of how VLM models can be exploited to create structured data in modern formats (like JSON) from unstructured data like a handwritten receipt.

Word of caution: Best to run this using Google Colab as it comes preinstalled with PyTorch and Transformers packages, required for this project. This is also useful if you share my handicap of having a MacBook.

I was able to get this JSON output for the image below. See if you can tune the parameters and do better.

```{   "store": "WILLIAMS' BOOK STORE",   "address": "708 SOUTH PACIFIC AVENUE San Pedro, Calif. 90731",   "phone": "832-3631",   "date": "2/15/1981",   "customer": {     "name": "Ellen Leonard",     "address": "1351 W 15th St",     "city": "SP",     "zip": "90732",     "phone": "832-3436"   },   "items": [     {       "title": "Great Tastes of Chinese Cooking",       "price": "12.95",       "tax": "0.08",       "total": "13.03"     }   ],   "notes": "ON ORDERED BOOKS THERE IS A POSSIBILITY OF A PRICE INCREASE.",   "footer": "MOORE BUSINESS FORMS, INC-M" }```

![alt text](https://penhopechest.com/wp-content/uploads/2012/04/handwritten-receipt-1981.jpg)

Image source: https://penhopechest.com/2012/04/05/the-age-of-the-handwritten-receipt/
