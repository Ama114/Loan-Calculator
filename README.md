# Loan-Calculator


# 🧮 Professional Loan Calculator

A professional, bank-grade loan calculator built with pure HTML, CSS, and JavaScript. Perfect for banks, finance companies, personal finance websites, and individual users planning their loans.

![Loan Calculator](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### Core Functionality
- **Accurate EMI Calculation** - Uses standard banking formula: `[P × R × (1+R)^N] / [(1+R)^N-1]`
- **Multi-Currency Support** - 8 major currencies including USD, EUR, GBP, INR, LKR, AUD, CAD, JPY
- **Flexible Tenure Options** - Calculate loans in months or years
- **Real-time Calculations** - Instant updates as you type
- **Input Validation** - Handles invalid inputs gracefully

### Visual Features
- **Interactive Pie Chart** - Visual breakdown of principal vs interest (Canvas API)
- **Detailed Amortization Schedule** - Month-by-month payment breakdown
- **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Professional UI** - Clean, modern interface with finance-industry color scheme
- **Helpful Tooltips** - User-friendly guidance for each input field

### Additional Features
- **Payment Summary Cards** - Quick overview of key figures
- **Expandable Schedule Table** - Collapsible detailed payment schedule
- **Reset Functionality** - One-click reset to default values
- **Legal Disclaimer** - Professional disclaimer for financial estimates

 

## 💻 Usage

### Basic Loan Calculation

1. **Select Currency** - Choose from 8 supported currencies
2. **Enter Loan Amount** - The total amount you want to borrow
3. **Set Interest Rate** - Annual interest rate (% per year)
4. **Choose Loan Tenure** - Duration in months or years
5. **View Results** - EMI and breakdown appear instantly

### Understanding the Results

- **Monthly EMI** - Your fixed monthly payment amount
- **Principal Amount** - The original loan amount
- **Total Interest** - Total interest paid over the loan period
- **Total Amount Payable** - Principal + Interest
- **Payment Breakdown Chart** - Visual representation of principal vs interest
- **Repayment Schedule** - Detailed month-by-month breakdown

## 🔧 Technical Details

### EMI Formula

```
EMI = [P × R × (1+R)^N] / [(1+R)^N-1]

Where:
P = Principal loan amount
R = Monthly interest rate (Annual Rate / 12 / 100)
N = Total number of months
```

### Supported Currencies

| Currency | Symbol | Code |
|----------|--------|------|
| US Dollar | $ | USD |
| Euro | € | EUR |
| British Pound | £ | GBP |
| Indian Rupee | ₹ | INR |
| Sri Lankan Rupee | Rs | LKR |
| Australian Dollar | A$ | AUD |
| Canadian Dollar | C$ | CAD |
| Japanese Yen | ¥ | JPY |

 
## 📱 Responsive Design

The calculator automatically adapts to different screen sizes:

- **Desktop** (1200px+): Two-column layout with side-by-side input/output
- **Tablet** (768px-1199px): Two-column layout with adjusted spacing
- **Mobile** (<768px): Single-column stacked layout for easy touch interaction

## 🎨 Customization

### Changing Colors

The calculator uses CSS variables that can be easily modified:

**Primary Colors:**
- Blue: `#1976d2` (EMI card, principal)
- Green: `#4caf50` (interest amounts)
- Gray: Various shades for backgrounds and borders


## 📊 Example Calculations

### Example 1: Home Loan
- **Loan Amount:** $200,000
- **Interest Rate:** 6.5% per year
- **Tenure:** 20 years (240 months)
- **Result:** EMI ≈ $1,491.96

### Example 2: Personal Loan
- **Loan Amount:** Rs 500,000 (LKR)
- **Interest Rate:** 15% per year
- **Tenure:** 3 years (36 months)
- **Result:** EMI ≈ Rs 17,328.07

### Example 3: Car Loan
- **Loan Amount:** ₹800,000 (INR)
- **Interest Rate:** 9% per year
- **Tenure:** 5 years (60 months)
- **Result:** EMI ≈ ₹16,604.70

## ⚠️ Important Notes

1. **Estimates Only** - Results are for informational purposes
2. **Actual Terms May Vary** - Lenders may have different rates and conditions
3. **Additional Costs** - Processing fees, insurance, etc. not included
4. **Consult Professionals** - Always verify with financial advisors or banks

## 🔒 Privacy & Security

- **No Data Collection** - All calculations happen in your browser
- **No Server Calls** - Completely client-side application
- **No Cookies** - No tracking or data storage
- **Offline Capable** - Works without internet connection once loaded

## 📄 File Structure

```
loan-calculator/
│
├── loan-calculator.html    # Main calculator file (standalone)
├── README.md               # This documentation file
└── LICENSE                 # MIT License file (optional)
```

 

## 🌟 Use Cases

### For Businesses
- Bank websites
- Credit union portals
- Finance company websites
- Loan broker platforms
- Financial advisory services

### For Individuals
- Personal finance planning
- Loan comparison
- Budget planning
- Financial education
- Home buying preparation

 
## 🎯 Roadmap

Potential future enhancements:

- [ ] Print functionality for reports
- [ ] PDF export of amortization schedule
- [ ] Comparison mode for multiple loans
- [ ] Extra payment calculator
- [ ] Loan refinancing calculator
- [ ] Dark mode toggle
- [ ] Multiple language support
- [ ] Save calculations locally

 

---
 
