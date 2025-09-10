# bitDAG
oxt.me replacer!
--
--

[let me watch forsen t3 streams](https://cwallet.com/t/MIXHFP7D)

# Bitcoin Transaction DAG Viewer

A powerful web-based tool for visualizing Bitcoin transactions as interactive Directed Acyclic Graphs (DAGs). Track transaction flows, explore address histories, and analyze blockchain data with an intuitive interface.

![Screenshot](https://via.placeholder.com/800x400?text=Bitcoin+Transaction+DAG+Viewer+Screenshot)

## Features

### 🌐 Interactive DAG Visualization
- **Circular Nodes**: Visual representation where node size reflects Bitcoin transaction value
- **Hierarchical Layout**: Transactions flow from left to right for intuitive understanding
- **Color-Coded Elements**: Different colors for transactions, inputs, outputs, and addresses
- **Interactive Tooltips**: Hover over nodes for detailed information

### 🔍 Transaction Tracking
- **Endless Exploration**: Click on any node to expand and explore related transactions
- **Address History**: View complete transaction history for any Bitcoin address
- **Previous Transactions**: Trace back through transaction inputs to their origins
- **Real-time Data**: Fetches live data from the Mempool.space API

### 📊 Comprehensive Details Panel
- **Transaction Information**: View complete details including fees, size, and confirmation status
- **Input/Output Breakdown**: See all transaction inputs and outputs with amounts
- **Address Analytics**: Track total received, transaction counts, and activity patterns
- **Filtering Options**: Filter transactions by confirmation status (all, confirmed, unconfirmed)

### 🎨 User-Friendly Interface
- **Responsive Design**: Works on desktop and mobile devices
- **Smooth Scrolling**: Optimized scrolling behavior for all panels
- **Visual Legend**: Clear legend explaining node types and colors
- **Loading Indicators**: Visual feedback during data fetching

## Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API access

### Local Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bitcoin-dag-viewer.git
   cd bitcoin-dag-viewer
   ```

2. **Serve the application**
   - **Option 1: Using Python**
     ```bash
     # Python 3
     python -m http.server 8000
     ```
   
   - **Option 2: Using Node.js**
     ```bash
     # Install serve if you don't have it
     npm install -g serve
     serve .
     ```
   
   - **Option 3: Using Live Server (VS Code extension)**
     - Install the Live Server extension in VS Code
     - Right-click `index.html` and select "Open with Live Server"

3. **Access the application**
   Open your browser and navigate to `http://localhost:8000`

## Usage Guide

### Basic Usage

1. **Load a Transaction**
   - Enter a Bitcoin transaction ID in the input field
   - Click "Load Transaction" or press Enter
   - The transaction will be visualized as a DAG

2. **Explore the Visualization**
   - **Hover over nodes** to see detailed information
   - **Click on input nodes** to explore previous transactions
   - **Click on output nodes** to view address transaction history
   - **Use mouse controls** to pan, zoom, and navigate the graph

3. **Analyze Transaction Details**
   - View comprehensive information in the right panel
   - Filter transactions by confirmation status
   - Click on any transaction in the address history to load it

### Advanced Features

#### Transaction Tracking
- **Input Expansion**: Click on input nodes to trace back through transaction history
- **Address Exploration**: Click on output nodes to see all transactions for that address
- **Endless Tracking**: Continue exploring related transactions without limitations

#### Filtering and Analysis
- **Confirmation Status**: Filter between confirmed and unconfirmed transactions
- **Address Analytics**: View statistics about address activity and transaction volumes
- **Value Visualization**: Node sizes represent Bitcoin amounts for quick visual analysis

### Example Transaction IDs for Testing

#### Small Transaction
```
812eebad193506383b14dfe52fa643c84961cb82fb372f532617e369378f3704
```

#### Medium Transaction
Look for transactions around 1-10 BTC on blockchain explorers

#### Large Transaction
```
f4184fc596403b9d638783cf57adfe4c75c605f6356fbc91338530e9831e9e16
```
(Famous 10,000 BTC Bitcoin pizza transaction)

## Technology Stack

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox and responsive design
- **JavaScript (ES6+)**: Interactive functionality and API integration
- **Vis.js**: Graph visualization library for DAG rendering

### APIs
- **Mempool.space API**: Real-time Bitcoin blockchain data
  - Transaction details: `/api/tx/{txid}`
  - Address transactions: `/api/address/{address}/txs`
  - Address information: `/api/address/{address}`

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## API Reference

### Used Endpoints

#### Transaction Details
```
GET https://mempool.space/api/tx/{txid}
```
Retrieves detailed information about a specific transaction.

#### Address Transactions
```
GET https://mempool.space/api/address/{address}/txs
```
Fetches all transactions for a specific Bitcoin address.

#### Address Information
```
GET https://mempool.space/api/address/{address}
```
Gets statistics and information about a Bitcoin address.

### Rate Limiting
- The Mempool.space API has rate limits
- The application handles 429 errors gracefully
- Consider implementing caching for high-usage scenarios

## Project Structure

```
bitcoin-dag-viewer/
├── index.html          # Main application file
├── README.md           # This file
├── assets/             # Images and static assets (if any)
└── docs/               # Additional documentation (if any)
```

## Contributing

We welcome contributions to improve the Bitcoin Transaction DAG Viewer! Please follow these guidelines:

### Development Workflow

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Test thoroughly**
5. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
6. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### Code Style Guidelines
- Use modern JavaScript (ES6+) features
- Follow existing code formatting and structure
- Add comments for complex functionality
- Ensure responsive design for all components

### Feature Requests
- Open an issue with the "enhancement" tag
- Provide a clear description of the requested feature
- Explain the use case and benefits

### Bug Reports
- Open an issue with the "bug" tag
- Provide steps to reproduce the issue
- Include browser and environment information
- Add screenshots if applicable

## Roadmap

### Planned Features
- [ ] **Export Functionality**: Export graphs as images (PNG/SVG)
- [ ] **Multi-Currency Support**: Extend to other cryptocurrencies
- [ ] **Address Clustering**: Group related addresses automatically
- [ ] **Time Filtering**: Filter transactions by date range
- [ ] **Enhanced Analytics**: Advanced transaction statistics and insights
- [ ] **Dark Mode**: Add dark theme option
- [ ] **Mobile App**: React Native mobile version

### Performance Improvements
- [ ] **Optimized Rendering**: Improve performance for large graphs
- [ ] **Caching Layer**: Implement Redis caching for API responses
- [ ] **Lazy Loading**: Load transaction data on demand
- [ ] **Web Workers**: Offload heavy processing to background threads

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Mempool.space** for providing the excellent blockchain API
- **Vis.js** for the powerful graph visualization library
- The Bitcoin community for inspiration and feedback

## Support

If you find this project useful, please consider:
- ⭐ Starring the repository on GitHub
- 🐛 Reporting bugs and issues
- 💡 Suggesting new features
- 📢 Sharing with others who might find it helpful

## Contact
xno.me/forsenlover69
--

