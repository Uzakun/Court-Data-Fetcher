# Court Data Fetcher & Mini-Dashboard

A web application for fetching and displaying case information from Indian courts (Delhi High Court demo).

## 🏛️ Features

- **Case Search**: Search by Case Type, Number, and Filing Year
- **Case Details Display**: Shows parties, filing dates, hearing dates, and case status
- **Document Access**: Links to orders and judgments (PDF downloads)
- **Query History**: Maintains log of all searches
- **Responsive Design**: Works on desktop and mobile devices

## 🧪 Demo Data

Try these test cases:
- **CRL/1234/2024** - Criminal case with multiple documents
- **CWP/5678/2023** - Civil writ petition 
- **FAO/9101/2022** - First appeal case

## 🚀 Deployment

This application is deployed on Vercel and can be accessed at: [Your Vercel URL]

### Local Development

1. Clone the repository
2. Open `index.html` in a web browser
3. Or run a local server:
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

## 🔧 Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Data**: Mock data simulating court database
- **Storage**: In-memory query logging (localStorage not used due to deployment constraints)
- **Styling**: Custom CSS with modern gradient design

## ⚖️ Legal Notice

This is a demonstration application with mock data. In a production environment:
- Ensure compliance with court website terms of service
- Implement proper rate limiting
- Add authentication and security measures
- Use real database storage

## 📝 License

MIT License - Feel free to modify and use for educational purposes.

---

**Target Court**: Delhi High Court (Demo Implementation)  
**Status**: Prototype/Demo Version  
**Last Updated**: August 2024