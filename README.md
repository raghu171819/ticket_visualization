# ticket_visualization
# Customer Support Ticket Analysis with Sentence Embeddings

This project is an assignment to analyze customer support tickets. The script categorizes tickets into **High**, **Medium**, or **Low** priority based on keywords, and then uses the `sentence-transformers` library to generate numerical embeddings for each ticket.

The primary goal is to explore how sentence embeddings can capture the semantic meaning of support tickets and to visualize the results to see if similar tickets cluster together.

---
## How to Run the Code

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```

2.  **Install dependencies:**
    Make sure you have Python installed. Then, run the following command to install the necessary libraries:
    ```bash
    pip install datasets pandas sentence-transformers scikit-learn matplotlib
    ```

3.  **Execute the script:**
    You can run the analysis by executing the Jupyter Notebook (`ticket_analysis.ipynb`) cell by cell.

---
## Results

The script generates a 2D visualization of the ticket embeddings using t-SNE. This plot shows how tickets are grouped based on their content. As seen in the image below, many tickets with the same priority level (especially "High" priority) form distinct clusters, demonstrating the effectiveness of the embedding model.

### Ticket Visualization
<img width="1008" height="855" alt="ticket_visualization (1)" src="https://github.com/user-attachments/assets/fb2a666b-4ef1-448c-815a-28887417095c" />
