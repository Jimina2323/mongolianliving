# Mongolian Realty
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Property Marketplace</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Property Marketplace</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#rent">Rent Properties</a></li>
            <li><a href="#sell">Sell Properties</a></li>
            <li><a href="javascript:void(0);" onclick="openSearchModal()">Search</a></li>
            <!-- Add a button to open the search modal -->
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <h2>Welcome to our Property Marketplace</h2>
    <p>Find your dream home or sell your property with us!</p>
</section>

<section id="search">
    <!-- Add a search modal -->
    <div id="searchModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeSearchModal()">&times;</span>
            <h2>Search Properties</h2>
            <input type="text" id="searchInput" placeholder="Search...">
            <button onclick="searchProperties()">Search</button>
            <div id="searchResults"></div>
        </div>
    </div>
</section>

<script src="script.js"></script>

<footer>
    <p>&copy; 2024 Property Marketplace</p>
</footer>

</body>
</html>
import tkinter as tk

def search_button_clicked():
    search_query = entry.get()
    # Perform search functionality using the search_query

root = tk.Tk()
root.title("Search Window")

label = tk.Label(root, text="Enter search query:")
label.pack()

entry = tk.Entry(root)
entry.pack()

search_button = tk.Button(root, text="Search", command=search_button_clicked)
search_button.pack()

root.mainloop()
