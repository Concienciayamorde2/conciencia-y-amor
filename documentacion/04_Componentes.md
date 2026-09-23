/* ===========================
   NAVBAR
=========================== */

.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 60px;
    background:var(--card);
    box-shadow:var(--shadow);

}

.logo{
    display:flex;
    align-items:center;
    gap:15px;
    color:var(--primary);

}

.logo strong{
    font-size:1.3rem;
}

.logo p{
    margin:0;
    color:var(--text);
    font-size:.85rem;

}

.logo-icon{
    font-size:2rem;

}

nav ul{

    display:flex;
    list-style:none;
    gap:30px;

}

nav a{

    text-decoration:none;
    color:var(--text);
    font-weight:500;
    transition:.3s;

}

nav a:hover{
    color:var(--primary);

}

.btn-primary{
    background:var(--primary);
    color:white;
    padding:12px 22px;
    border-radius:var(--radius);
    text-decoration:none;
    font-weight:bold;
    transition:.3s;

}

.btn-primary:hover{
    background:var(--primary-dark);

}