# CHCCapitalpartners
/* General Styles */
body {
  font-family: 'Inter', sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  color: #333;
  background-color: #f9f9f9;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
}

h1, h2, h3 {
  color: #0a1f44;
}

/* Partner Section */
.partner-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
  text-align: center;
}

.partner-card img {
  width: 160px;
  height: 160px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 1rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.partner-card h3 {
  font-size: 1.1rem;
  margin-bottom: 0.3rem;
  color: #0a1f44;
}

.partner-card p {
  font-size: 0.95rem;
  color: #555;
}

/* Services Grid */
.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2.5rem;
  margin-top: 2rem;
}

.service-item {
  display: flex;
  gap: 1.5rem;
  align-items: flex-start;
  padding-bottom: 1.5rem;
  border-bottom: 1px solid #e0e0e0;
}

.service-item:last-child {
  border-bottom: none;
}

.service-item .icon img {
  width: 50px;
  height: 50px;
}

.service-item .content h3 {
  font-size: 1.4rem;
  margin: 0 0 0.5rem;
  color: #0a1f44;
}

.service-item .content p {
  font-size: 1rem;
  margin: 0 0 0.75rem;
  color: #333;
}

.service-item .content a {
  font-weight: 600;
  color: #0a1f44;
  text-decoration: none;
  border-bottom: 2px solid transparent;
  transition: border-color 0.2s ease;
}

.service-item .content a:hover {
  border-color: #0a1f44;
}
