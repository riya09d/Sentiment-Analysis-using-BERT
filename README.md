
# Sentiment Analysis using BERT

This project demonstrates sentiment analysis using a pre-trained BERT model. It utilizes the Hugging Face transformers library to perform sentiment analysis on reviews collected from the Yelp website.

## Installation 

To run this project, you need to install the required dependencies. You can install them using the following commands:

```bash
pip install torch torchvision torchaudio
pip install transformers requests beautifulsoup4 pandas numpy
```

## Usage

1. **Import Libraries**: Start by importing the necessary libraries and modules.

2. **Load Pre-trained Model**: Load the pre-trained BERT model and tokenizer.

3. **Encode Text and Analyze Sentiment**: Encode the text you want to analyze using the tokenizer, pass the encoded tokens through the BERT model to get the sentiment logits, and determine the sentiment score based on the maximum logit value.

4. **Collect and Analyze Reviews**: Collect reviews from a website (e.g., Yelp) using web scraping techniques, perform sentiment analysis on the collected reviews, and store the results in a DataFrame.

## Dependencies

- torch
- torchvision
- torchaudio
- transformers
- requests
- beautifulsoup4
- pandas
- numpy

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your changes to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.

## Credits

- [Hugging Face](https://huggingface.co/) - For providing the transformers library and pre-trained BERT models.
- [Yelp](https://www.yelp.com/) - Source of the review data used in this project.

