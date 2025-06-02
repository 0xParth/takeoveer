# Takeoveer 🎯

Subdomain Takeover Vulnerability Scanner

## 🌐 Live Demo

Visit: [https://takeoveer.vercel.app](https://takeoveer.vercel.app)

## 📌 Overview

Takeoveer is a web-based tool designed to help security researchers and bug bounty hunters identify potential subdomain takeover vulnerabilities. It checks for misconfigured DNS records and abandoned cloud services that could be exploited by attackers.

## 🚀 Features

- **Real-time Scanning**: Instant subdomain takeover detection
- **Multiple Service Checks**: Supports various cloud providers and services
- **User-friendly Interface**: Clean, intuitive web interface
- **Fast Results**: Optimized for quick vulnerability identification
- **No Installation Required**: Web-based tool accessible from any browser

## 🔍 How It Works

1. Enter a domain or subdomain
2. The tool checks for:
   - Dangling CNAME records
   - Abandoned S3 buckets
   - Unclaimed GitHub Pages
   - Misconfigured Azure services
   - And many more...
3. Get instant results with vulnerability details

## 💻 Local Development

```bash
# Clone the repository
git clone https://github.com/0xParth/takeoveer.git
cd takeoveer

# Install dependencies (if any)
npm install

# Run locally
npm run dev

# Build for production
npm run build
```

## 🛡️ Supported Services

- Amazon S3
- Amazon CloudFront
- GitHub Pages
- Heroku
- Azure
- Shopify
- Tumblr
- WordPress
- And many more...

## 📊 API Usage

```javascript
// Example API request
fetch('https://takeoveer.vercel.app/api/check', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
  },
  body: JSON.stringify({
    domain: 'subdomain.example.com'
  })
})
```

## ⚠️ Responsible Disclosure

This tool is intended for:
- Security researchers
- Bug bounty hunters
- Authorized penetration testing
- Educational purposes

Always ensure you have permission before testing any domain you don't own.

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License.

## 👤 Author

**0xParth**
- GitHub: [@0xParth](https://github.com/0xParth)
- Twitter: [@0xparth](https://twitter.com/0xparth)
- Instagram: [@bug_xs](https://instagram.com/bug_xs)

## 🙏 Acknowledgments

- Inspired by the bug bounty community
- Thanks to all contributors and testers
