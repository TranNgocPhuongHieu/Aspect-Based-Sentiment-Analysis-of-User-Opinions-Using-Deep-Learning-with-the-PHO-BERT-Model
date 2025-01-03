# Aspect-Based-Sentiment-Analysis-of-User-Opinions-Using-Deep-Learning-with-the-PHO-BERT-Model
1. Crawl data in shopee: In this project use:

- Bs4
- Request

2. Labeling :

- Use gpt4 for assign labeling aspect
- About aspect : Chất lượng sản phẩm, Dịch vụ khách hàng, Giá cả, Giao hàng, Đóng gói sản phẩm
- Example : Chất lượng sản phẩm; Dịch vụ khách hàng, Giá cả; Giá cả, Giao hàng, Đóng gói sản phẩm,...
- About rating : negative, positive, neutral A comment can have more than the above aspects. total aspect : 33 total rating : 3

3. Data processing:

- Delete white space, stop word, teen code,...
- Tokenization

4. Model :

- Pho-bert
- Pho-bert + 2 MLP
- Pho-bert + CNN + LSTM
- Pho-bert + LSTM + CNN

# Summary
This is the topic of identifying customer emotions through all aspects, to help business customers easily adjust their sales strategies to develop their businesses.
