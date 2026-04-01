import React from 'react';
import './styles/Nexus.css';

function Navbar() {
  return (
    <nav className="navbar">
      <div className="navbar-brand">
        🎓 Nexus
      </div>
      <ul className="nav-links">
        <li><a href="/">Dashboard</a></li>
        <li><a href="/expenses">Expenses</a></li>
        <li><a href="/stocks">Stocks</a></li>
        <li><a href="/learn">Learn</a></li>
        <li><a href="/challenges">Challenges</a></li>
      </ul>
    </nav>
  );
}

export default Navbar;

