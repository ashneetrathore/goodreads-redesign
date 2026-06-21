# :books: GOODREADS PROFILE REDESIGN

## :open_book: OVERVIEW
Date: December 2024\
Designer(s): Ashneet Rathore, Rachel Balta, Ananya Srikanth Kashyap, Angela Wang, Sovit Nayak\

Goodreads Profile Redesign is a UI/UX case study focused on improving the user profile page on the Goodreads website. The project followed a three-phase design process: user research, synthesis, and redesign. Early user research focused on identifying a specific feature or page within Goodreads to improve, leading our team to select the profile page as a key area for redesign. This repository serves as a centralized hub for all project artifacts, including research documentation and Figma pages.

## :package: PROJECT ARTIFACTS

| Phase          | Artifacts |
|----------------|-----------|
| User Research  | Interview notes - [View PDF in repo](interview-notes.pdf)<br> Interview insights - [View on Figjam](https://www.figma.com/board/5GT1Rb2KXfnt9kRIGtVZwK/Interview-Insights?t=ZRDpZYlBwcDJb6Z0-6) <br> Expert analysis - [View PDF in repo](expert-analysis.pdf)
| Synthesis      | User persona - [View on Figjam](https://www.figma.com/board/Xu5r0rDU7HzIngWXGpjW6s/User-Persona?t=ZRDpZYlBwcDJb6Z0-6)
| Redesign         | Wireframes and lo-fi mockups - [View on Figma](https://www.figma.com/design/dqtQhJabkz1mjxVUuWmtLP/Profile-Page-Mockups?node-id=0-1&p=f&t=TKr9NqI34Na5QF89-0) <br> Hi-fi mockups (core experience) - [View on Figma](https://www.figma.com/design/dqtQhJabkz1mjxVUuWmtLP/Profile-Page-Mockups?node-id=31-12&p=f&t=TKr9NqI34Na5QF89-0) <br> Hi-fi mockups (extended features) - [View on Figma](https://www.figma.com/design/dqtQhJabkz1mjxVUuWmtLP/Profile-Page-Mockups?node-id=223-124&t=ZRDpZYlBwcDJb6Z0-1) <br> Interactive prototype - [View on Figma](https://www.figma.com/proto/dqtQhJabkz1mjxVUuWmtLP/Profile-Page-Mockups?node-id=31-12&t=ZRDpZYlBwcDJb6Z0-1) <br> Prototype demo - [View on Youtube](https://www.youtube.com/watch?v=iqQ_Mo10PUE)

## :memo: CASE STUDY SUMMARY
### :mag: USER RESEARCH
Goodreads is a social platform created for readers to discover, catalog, and share books. Users are able to see what their friends are reading and reviewing, publish book reviews, and organize books into custom shelves. Our target subpopulation for the case study was new adult avid readers, ages 18 and 30. Most interviewees expressed dissatisfaction with the Goodreads Discover page, noting that it populates long book lists with outdated, generic titles, instead of offering a streamlined selection of tailored recommendations. Another discovery made was that users placed significant trust in the Goodreads community, particularly in ratings and reviews. Together, these insights suggested that while many users do not rely on the algorithm for the discovery of books, they heavily depend on the community's input to guide their reading choices.

### :bulb: SYNTHESIS
Based on these insights, we identified an opportunity to emphasize user-driven discovery rather than algorithmic recommendations. We theorized that users would much rather explore recommendations shown on other user's profiles instead of relying on the Discover page.

User Story:
> "As an avid reader, I want to have a clear profile that accurately represents my reading preferences, so that other users can better identify my tastes and get recommendations from my page, and vice versa."

### :art: REDESIGN
Goodreads users expressed frustration with having jumbled profiles that fail to clearly showcase their reading tastes. The current state of the profile page is hard to navigate, causing cognitive overload due to its various sections and lack of visual hierarchy. It's hard for users to find key information, such as favorite books, on a profile, and thus, fails to present a focus on the user's reading tastes.

To address these issues, we introduced several core design changes. First, we implemented a navigation bar to combat the overwhelming nature of the profile page, allowing users to easily explore sections like a user's bookshelves, updates, and stats. Users are able to quickly access the information they care about without having to sift through disjointed sections. Second, we added a *Top 5 Recommendations* section, complete with user-authored blurbs, which are comments about the books they recommended. Other users can browse this section and add books to their *Want to Read* shelves, enhancing the critical aspect of book discovery. Lastly, we moved the *Now Reading* section alongside the *Top 5 Recommendations* section to provide immediate context into a user's current interests.

To further enhance the redesigned profile experience, we added three features to the original hi-fi mockup:
1. *Top 5 Quotes*\
A user-editable section similar to the *Top 5 Recommendations* section, allowing users to share their favorite quotes and update them as they see fit.
2. *Reading by Genre*\
An automatically generated pie chart that visualizes the distribution of genres found in the user's *Already Read* shelf, using Goodreads' predefined genre categories. The chart provides a more accurate reflection of the genres the user engages with and highlights which genre the user prefers over others. This section replaces the small, hidden *Favorite Genres* section, which required users to manually select and edit their favorite genres.
3. *Reading by Mood*\
An automatically generated pie chart that visualizes the distribution of moods found in the user's *Already Read* shelf, using a predefined set of mood categories. This section is inspired by StoryGraph's feature of organizing books by their tone or atmosphere, and it offers a new way for users to explore reading preferences by mood.
