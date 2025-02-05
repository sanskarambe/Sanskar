import re

def count_words(text):
    # Convert text to lowercase and remove punctuation
    text = text.lower()  # Normalize case
    text = re.sub(r'[^\w\s]', '', text)  # Remove punctuation using regex
    
    # Split the text into words based on spaces
    words = text.split()
    return len(words), words  # Return both word count and the list of words

def main():
    # Prompt user for input
    text = input("Enter a sentence or paragraph: ")
    
    # Handle empty input or input with only spaces
    if not text.strip():
        print("Error: No input provided!")
    else:
        # Count words and get the word list
        word_count, words = count_words(text)
        
        # Display the results
        print(f"The number of words is: {word_count}")
        print("Words:", words)

# Call the main function to execute the program
if __name__ == "__main__":
    main()
