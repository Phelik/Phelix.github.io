# Phelix.github.io
/* Reset default styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styling */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Header styling */
header {
    background-color: #0044cc;
    color: white;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo h1 {
    font-size: 2em;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.1em;
}

/* Content section styling */
.content-section {
    padding: 20px;
    margin: 20px 0;
}

.content-section h2 {
    font-size: 1.8em;
    margin-bottom: 10px;
}

.content-section p {
    font-size: 1.2em;
}

/* Table styling for jadwal dokter */
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

table th, table td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

table th {
    background-color: #f4f4f4;
}

/* Footer styling */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
