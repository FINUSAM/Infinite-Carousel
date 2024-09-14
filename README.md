# Infinite Carousel Card Slider

## Project Description
This project implements an infinite carousel card slider where cards are displayed inside a slider and can be added dynamically using various methods. The slider uses a smooth shifting method to give the appearance of an infinite carousel. The project was built iteratively, with improvements in each version.

## Features

### V1: Initial Slider with Static Cards
- Created a slider (`div`) that holds multiple cards.
- Added basic styling to the cards to display them neatly in the slider.
  
### V2: Dynamic Card Addition
- Implemented functionality to dynamically add cards into the slider.
- The slider can now adjust to the number of cards added at runtime.

### V3: Unlimited Cards Using a Counter
- Added the ability to append an unlimited number of cards using a counter variable.
- Each card is uniquely identified and added based on the counter.

### V4: Unlimited Cards Using Card Data List
- Replaced the counter-based card generation with a list of card data.
- Cards are now generated and added to the slider based on the data from this list.
- Easier to manage and update card content dynamically.

### V5: Infinite Slider (Shifting Method) - Final Version
- Implemented an infinite scrolling slider.
- The cards shift continuously, always keeping the center of the slider populated with a card.
- New method introduced for smoother, seamless transitions.

## Installation & Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/infinite-card-slider.git
2. Open the below file in your browser
   ```bash
   carousel v5 - unlimited scrolling.html
