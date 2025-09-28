* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #333;
    color: white;
    padding: 10px 20px;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.menu-icon {
    display: none;
    font-size: 28px;
    cursor: pointer;
    user-select: none;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    transition: color 0.3s;
}

.nav-links li a:hover {
    color: lightblue;
}

#menu-toggle {
    display: none;
}

@media (max-width: 768px) {
    .menu-icon {
        display: block;
    }

    .nav-links {
        display: none;
        position: absolute;
        top: 60px;
        right: 0;
        background: #333;
        width: 200px;
        flex-direction: column;
        text-align: center;
        padding: 10px 0;
    }

    #menu-toggle:checked + .menu-icon + .nav-links {
        display: flex;
    }

    .nav-links li {
        margin: 15px 0;
    }
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #333;
    color: white;
    padding: 10px 20px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.menu-icon {
    display: none;
    font-size: 28px;
    cursor: pointer;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    transition: color 0.3s;
}

.nav-links li a:hover {
    color: lightblue;
}

#menu-toggle {
    display: none;
}

@media (max-width: 768px) {
    .menu-icon {
        display: block;
    }

    .nav-links {
        display: none;
        position: absolute;
        top: 60px;
        right: 0;
        background: #333;
        width: 200px;
        flex-direction: column;
        text-align: center;
        padding: 10px 0;
    }

    #menu-toggle:checked + .menu-icon + .nav-links {
        display: flex;
    }

    .nav-links li {
        margin: 15px 0;
    }
}
