<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrackSmart - Student Expense Tracker</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
    <!-- React & ReactDOM -->
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <!-- Babel Standalone for JSX -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
    
<style>
        :root {
            --primary: #10b981;
            --primary-dark: #059669;
            --primary-light: #d1fae5;
            --accent: #f59e0b;
            --bg: #fafaf9;
            --surface: #ffffff;
            --text-primary: #1c1917;
            --text-secondary: #57534e;
            --text-muted: #a8a29e;
            --border: #e7e5e4;
            --error: #ef4444;
            --shadow: 0 1px 3px rgba(0, 0, 0, 0.05), 0 1px 2px rgba(0, 0, 0, 0.1);
            --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Manrope', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #fafaf9 0%, #f5f5f4 100%);
            color: var(--text-primary);
            line-height: 1.6;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
        }

        /* Header */
        .header {
            background: var(--surface);
            border-bottom: 1px solid var(--border);
            position: sticky;
            top: 0;
            z-index: 100;
            backdrop-filter: blur(10px);
            box-shadow: var(--shadow);
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 0.75rem;
        }

        .logo-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 800;
            color: white;
            font-size: 1.25rem;
            box-shadow: var(--shadow-lg);
        }

        .logo-text h1 {
            font-size: 1.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .logo-text p {
            font-size: 0.75rem;
            color: var(--text-muted);
            font-weight: 500;
        }

        .nav {
            display: flex;
            gap: 0.5rem;
        }

        .nav-btn {
            padding: 0.625rem 1.25rem;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 0.875rem;
            cursor: pointer;
            transition: all 0.2s;
            font-family: 'Manrope', sans-serif;
        }

        .nav-btn.active {
            background: var(--primary);
            color: white;
            box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3);
        }

        .nav-btn:not(.active) {
            background: transparent;
            color: var(--text-secondary);
        }

        .nav-btn:not(.active):hover {
            background: var(--primary-light);
            color: var(--primary-dark);
        }

        /* Main Content */
        .main-content {
            padding: 2rem 0;
            animation: fadeIn 0.4s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Dashboard Stats */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .stat-card {
            background: var(--surface);
            border-radius: 16px;
            padding: 1.5rem;
            border: 1px solid var(--border);
            box-shadow: var(--shadow);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .stat-card:hover {
            transform: translateY(-2px);
            box-shadow: var(--shadow-lg);
        }

        .stat-header {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            margin-bottom: 1rem;
        }

        .stat-icon {
            width: 40px;
            height: 40px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.25rem;
        }

        .stat-icon.primary {
            background: var(--primary-light);
            color: var(--primary-dark);
        }

        .stat-icon.accent {
            background: #fef3c7;
            color: #d97706;
        }

        .stat-icon.secondary {
            background: #dbeafe;
            color: #1e40af;
        }

        .stat-label {
            font-size: 0.875rem;
            font-weight: 600;
            color: var(--text-secondary);
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        .stat-value {
            font-size: 2.25rem;
            font-weight: 800;
            font-family: 'JetBrains Mono', monospace;
            color: var(--text-primary);
        }

        .stat-subtitle {
            font-size: 0.875rem;
            color: var(--text-muted);
            margin-top: 0.25rem;
        }

        /* Expense List */
        .expense-list {
            background: var(--surface);
            border-radius: 16px;
            border: 1px solid var(--border);
            overflow: hidden;
            box-shadow: var(--shadow);
        }

        .expense-list-header {
            padding: 1.5rem;
            border-bottom: 1px solid var(--border);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .expense-list-header h2 {
            font-size: 1.25rem;
            font-weight: 700;
        }

        .expense-item {
            padding: 1.25rem 1.5rem;
            border-bottom: 1px solid var(--border);
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: background 0.2s;
        }

        .expense-item:last-child {
            border-bottom: none;
        }

        .expense-item:hover {
            background: #fafaf9;
        }

        .expense-info {
            flex: 1;
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .expense-category-badge {
            width: 48px;
            height: 48px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            font-size: 1.125rem;
        }

        .expense-details {
            flex: 1;
        }

        .expense-category-name {
            font-weight: 600;
            color: var(--text-primary);
            margin-bottom: 0.25rem;
        }

        .expense-meta {
            display: flex;
            gap: 1rem;
            align-items: center;
            font-size: 0.875rem;
            color: var(--text-muted);
        }

        .expense-note {
            color: var(--text-secondary);
            font-size: 0.875rem;
            margin-top: 0.25rem;
        }

        .expense-amount {
            font-size: 1.5rem;
            font-weight: 700;
            font-family: 'JetBrains Mono', monospace;
            color: var(--text-primary);
        }

        .expense-actions {
            display: flex;
            gap: 0.5rem;
            margin-left: 1rem;
        }

        .icon-btn {
            width: 36px;
            height: 36px;
            border: none;
            border-radius: 8px;
            background: transparent;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s;
            font-size: 1rem;
        }

        .icon-btn:hover {
            background: var(--primary-light);
            color: var(--primary-dark);
        }

        .icon-btn.delete:hover {
            background: #fee2e2;
            color: var(--error);
        }

        /* Empty State */
        .empty-state {
            text-align: center;
            padding: 4rem 2rem;
        }

        .empty-state-icon {
            font-size: 4rem;
            margin-bottom: 1rem;
            opacity: 0.3;
        }

        .empty-state h3 {
            font-size: 1.25rem;
            font-weight: 600;
            color: var(--text-secondary);
            margin-bottom: 0.5rem;
        }

        .empty-state p {
            color: var(--text-muted);
            margin-bottom: 1.5rem;
        }

        /* Form */
        .form-card {
            background: var(--surface);
            border-radius: 16px;
            padding: 2rem;
            border: 1px solid var(--border);
            box-shadow: var(--shadow);
            max-width: 600px;
            margin: 0 auto;
        }

        .form-header {
            margin-bottom: 2rem;
        }

        .form-header h2 {
            font-size: 1.75rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }

        .form-header p {
            color: var(--text-muted);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-label {
            display: block;
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: var(--text-primary);
            font-size: 0.875rem;
        }

        .form-input,
        .form-textarea,
        .form-select {
            width: 100%;
            padding: 0.875rem 1rem;
            border: 2px solid var(--border);
            border-radius: 10px;
            font-size: 1rem;
            font-family: 'Manrope', sans-serif;
            transition: all 0.2s;
            background: var(--surface);
        }

        .form-input:focus,
        .form-textarea:focus,
        .form-select:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(16, 185, 129, 0.1);
        }

        .form-textarea {
            resize: vertical;
            min-height: 100px;
        }

        .category-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 0.75rem;
        }

        .category-btn {
            padding: 1rem;
            border: 2px solid var(--border);
            border-radius: 10px;
            background: var(--surface);
            cursor: pointer;
            font-weight: 600;
            font-size: 0.875rem;
            transition: all 0.2s;
            font-family: 'Manrope', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 0.5rem;
        }

        .category-btn:hover {
            border-color: var(--primary);
            transform: translateY(-2px);
        }

        .category-btn.active {
            border-color: transparent;
            color: white;
            box-shadow: var(--shadow-lg);
        }

        .category-icon {
            font-size: 1.5rem;
        }

        .btn {
            padding: 1rem 2rem;
            border: none;
            border-radius: 10px;
            font-weight: 700;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.2s;
            font-family: 'Manrope', sans-serif;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
            box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3);
        }

        .btn-primary:hover {
            background: var(--primary-dark);
            transform: translateY(-2px);
            box-shadow: 0 6px 16px rgba(16, 185, 129, 0.4);
        }

        .btn-secondary {
            background: var(--border);
            color: var(--text-secondary);
        }

        .btn-secondary:hover {
            background: #d6d3d1;
        }

        .btn-group {
            display: flex;
            gap: 1rem;
            margin-top: 2rem;
        }

        .btn-group .btn {
            flex: 1;
        }

        /* Charts */
        .chart-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .chart-card {
            background: var(--surface);
            border-radius: 16px;
            padding: 1.5rem;
            border: 1px solid var(--border);
            box-shadow: var(--shadow);
        }

        .chart-header {
            margin-bottom: 1.5rem;
        }

        .chart-header h3 {
            font-size: 1.125rem;
            font-weight: 700;
            color: var(--text-primary);
        }

        .chart-container {
            position: relative;
            height: 300px;
        }

        /* Month Selector */
        .month-selector {
            background: var(--surface);
            border-radius: 16px;
            padding: 1.5rem;
            border: 1px solid var(--border);
            box-shadow: var(--shadow);
            margin-bottom: 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .month-display {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--text-primary);
        }

        .month-nav {
            display: flex;
            gap: 0.5rem;
        }

        .month-nav-btn {
            width: 40px;
            height: 40px;
            border: 2px solid var(--border);
            border-radius: 10px;
            background: var(--surface);
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s;
            font-size: 1.25rem;
        }

        .month-nav-btn:hover {
            border-color: var(--primary);
            background: var(--primary-light);
            color: var(--primary-dark);
        }

        /* Category Breakdown */
        .category-breakdown {
            background: var(--surface);
            border-radius: 16px;
            padding: 1.5rem;
            border: 1px solid var(--border);
            box-shadow: var(--shadow);
            margin-bottom: 2rem;
        }

        .category-breakdown h3 {
            font-size: 1.25rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
        }

        .category-item {
            display: flex;
            align-items: center;
            gap: 1rem;
            padding: 1rem 0;
            border-bottom: 1px solid var(--border);
        }

        .category-item:last-child {
            border-bottom: none;
        }

        .category-color {
            width: 12px;
            height: 12px;
            border-radius: 50%;
        }

        .category-name {
            flex: 1;
            font-weight: 600;
            color: var(--text-primary);
        }

        .category-amount {
            font-weight: 700;
            font-family: 'JetBrains Mono', monospace;
            color: var(--text-primary);
        }

        .category-percentage {
            font-size: 0.875rem;
            color: var(--text-muted);
            margin-left: 0.5rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 1rem;
            }

            .nav {
                width: 100%;
            }

            .nav-btn {
                flex: 1;
            }

            .stats-grid {
                grid-template-columns: 1fr;
            }

            .stat-value {
                font-size: 1.75rem;
            }

            .expense-item {
                flex-direction: column;
                align-items: flex-start;
                gap: 1rem;
            }

            .expense-actions {
                margin-left: 0;
                width: 100%;
                justify-content: flex-end;
            }

            .category-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .chart-grid {
                grid-template-columns: 1fr;
            }

            .month-selector {
                flex-direction: column;
                gap: 1rem;
            }
        }

        @media (max-width: 480px) {
            .form-card {
                padding: 1.5rem;
            }

            .btn-group {
                flex-direction: column;
            }
        }

        /* Utility */
        .text-error {
            color: var(--error);
            font-size: 0.875rem;
            margin-top: 0.5rem;
        }
    </style>
</head>
<body>
    <div id="root"></div>

<script type="text/babel">
        const { useState, useEffect, useRef } = React;
    
        // ============================================
        // CATEGORY CONFIGURATION
        // ============================================
        const CATEGORIES = [
            { name: 'Food', icon: '🍕', color: '#f59e0b' },
            { name: 'Travel', icon: '🚗', color: '#3b82f6' },
            { name: 'Rent', icon: '🏠', color: '#8b5cf6' },
            { name: 'Study', icon: '📚', color: '#10b981' },
            { name: 'Fun', icon: '🎮', color: '#ec4899' },
            { name: 'Misc', icon: '📦', color: '#6b7280' }
        ];

        const getCategoryConfig = (categoryName) => {
            return CATEGORIES.find(c => c.name === categoryName) || CATEGORIES[5];
        };

        // ============================================
        // STORAGE SERVICE
        // ============================================
        const StorageService = {
            STORAGE_KEY: 'tracksmart_expenses',

            getExpenses() {
                try {
                    const data = localStorage.getItem(this.STORAGE_KEY);
                    return data ? JSON.parse(data) : [];
                } catch (error) {
                    console.error('Error loading expenses:', error);
                    return [];
                }
            },

            saveExpenses(expenses) {
                try {
                    localStorage.setItem(this.STORAGE_KEY, JSON.stringify(expenses));
                    return true;
                } catch (error) {
                    console.error('Error saving expenses:', error);
                    return false;
                }
            }
        };

        // ============================================
        // UTILITY FUNCTIONS
        // ============================================
        const formatCurrency = (amount) => {
            return new Intl.NumberFormat('en-IN', {
                style: 'currency',
                currency: 'INR',
                minimumFractionDigits: 0,
                maximumFractionDigits: 0
            }).format(amount);
        };

        const formatDate = (dateString) => {
            const date = new Date(dateString);
            return date.toLocaleDateString('en-IN', { 
                day: 'numeric', 
                month: 'short',
                year: 'numeric'
            });
        };

        const getMonthName = (monthIndex) => {
            const months = [
                'January', 'February', 'March', 'April', 'May', 'June',
                'July', 'August', 'September', 'October', 'November', 'December'
            ];
            return months[monthIndex];
        };

        // ============================================
        // MAIN APP COMPONENT
        // ============================================
        function ExpenseTracker() {
            const [expenses, setExpenses] = useState([]);
            const [currentView, setCurrentView] = useState('dashboard');
            const [selectedMonth, setSelectedMonth] = useState(new Date().getMonth());
            const [selectedYear, setSelectedYear] = useState(new Date().getFullYear());
            const [editingExpense, setEditingExpense] = useState(null);

            // Load expenses on mount
            useEffect(() => {
                const loadedExpenses = StorageService.getExpenses();
                setExpenses(loadedExpenses);
            }, []);

            // Save expenses whenever they change
            useEffect(() => {
                if (expenses.length > 0 || expenses.length === 0) {
                    StorageService.saveExpenses(expenses);
                }
            }, [expenses]);

            // Filter expenses by selected month
            const getMonthExpenses = () => {
                return expenses.filter(expense => {
                    const expenseDate = new Date(expense.date);
                    return expenseDate.getMonth() === selectedMonth && 
                           expenseDate.getFullYear() === selectedYear;
                });
            };

            // Calculate monthly summary
            const getMonthSummary = () => {
                const monthExpenses = getMonthExpenses();
                const total = monthExpenses.reduce((sum, exp) => sum + exp.amount, 0);

                // Category totals
                const byCategory = CATEGORIES.map(cat => {
                    const categoryTotal = monthExpenses
                        .filter(exp => exp.category === cat.name)
                        .reduce((sum, exp) => sum + exp.amount, 0);
                    return {
                        ...cat,
                        total: categoryTotal
                    };
                }).filter(cat => cat.total > 0);

                // Highest spending category
                const highest = byCategory.reduce((max, cat) => 
                    cat.total > (max?.total || 0) ? cat : max, null
                );

                // Average daily spending
                const daysInMonth = new Date(selectedYear, selectedMonth + 1, 0).getDate();
                const avgDaily = total / daysInMonth;

                return { total, byCategory, highest, avgDaily, count: monthExpenses.length };
            };

            const summary = getMonthSummary();

            // Add or update expense
            const handleSaveExpense = (expenseData) => {
                if (editingExpense) {
                    setExpenses(expenses.map(exp => 
                        exp.id === editingExpense.id ? { ...expenseData, id: editingExpense.id } : exp
                    ));
                } else {
                    setExpenses([...expenses, { ...expenseData, id: Date.now() }]);
                }
                setEditingExpense(null);
                setCurrentView('dashboard');
            };

            // Delete expense
            const handleDeleteExpense = (id) => {
                if (confirm('Are you sure you want to delete this expense?')) {
                    setExpenses(expenses.filter(exp => exp.id !== id));
                }
            };

            // Start editing
            const handleEditExpense = (expense) => {
                setEditingExpense(expense);
                setCurrentView('add');
            };

            // Cancel editing
            const handleCancelEdit = () => {
                setEditingExpense(null);
                setCurrentView('dashboard');
            };

            // Navigate months
            const changeMonth = (delta) => {
                let newMonth = selectedMonth + delta;
                let newYear = selectedYear;

                if (newMonth > 11) {
                    newMonth = 0;
                    newYear++;
                } else if (newMonth < 0) {
                    newMonth = 11;
                    newYear--;
                }

                setSelectedMonth(newMonth);
                setSelectedYear(newYear);
            };

            return (
                <>
                    <header className="header">
                        <div className="container">
                            <div className="header-content">
                                <div className="logo">
                                    <div className="logo-icon">₹</div>
                                    <div className="logo-text">
                                        <h1>TrackSmart</h1>
                                        <p>Expense Management</p>
                                    </div>
                                </div>
                                <nav className="nav">
                                    <button 
                                        className={`nav-btn ${currentView === 'dashboard' ? 'active' : ''}`}
                                        onClick={() => {
                                            setCurrentView('dashboard');
                                            setEditingExpense(null);
                                        }}
                                    >
                                        Dashboard
                                    </button>
                                    <button 
                                        className={`nav-btn ${currentView === 'add' ? 'active' : ''}`}
                                        onClick={() => setCurrentView('add')}
                                    >
                                        Add Expense
                                    </button>
                                    <button 
                                        className={`nav-btn ${currentView === 'summary' ? 'active' : ''}`}
                                        onClick={() => {
                                            setCurrentView('summary');
                                            setEditingExpense(null);
                                        }}
                                    >
                                        Summary
                                    </button>
                                </nav>
                            </div>
                        </div>
                    </header>

                    <main className="main-content">
                        <div className="container">
                            {currentView === 'dashboard' && (
                                <Dashboard 
                                    summary={summary}
                                    expenses={getMonthExpenses()}
                                    onEdit={handleEditExpense}
                                    onDelete={handleDeleteExpense}
                                    onAddClick={() => setCurrentView('add')}
                                />
                            )}

                            {currentView === 'add' && (
                                <ExpenseForm
                                    onSave={handleSaveExpense}
                                    onCancel={handleCancelEdit}
                                    editingExpense={editingExpense}
                                />
                            )}

                            {currentView === 'summary' && (
                                <Summary
                                    summary={summary}
                                    expenses={expenses}
                                    selectedMonth={selectedMonth}
                                    selectedYear={selectedYear}
                                    onMonthChange={changeMonth}
                                />
                            )}
                        </div>
                    </main>
                </>
            );
        }

        // ============================================
        // DASHBOARD COMPONENT
        // ============================================
        function Dashboard({ summary, expenses, onEdit, onDelete, onAddClick }) {
            return (
                <div>
                    <div className="stats-grid">
                        <div className="stat-card">
                            <div className="stat-header">
                                <div className="stat-icon primary">💰</div>
                                <span className="stat-label">This Month</span>
                            </div>
                            <div className="stat-value">{formatCurrency(summary.total)}</div>
                            <div className="stat-subtitle">{summary.count} transactions</div>
                        </div>

                        <div className="stat-card">
                            <div className="stat-icon accent">📊</div>
                            <div className="stat-header">
                                <span className="stat-label">Daily Average</span>
                            </div>
                            <div className="stat-value">{formatCurrency(summary.avgDaily)}</div>
                            <div className="stat-subtitle">Based on {new Date(new Date().getFullYear(), new Date().getMonth() + 1, 0).getDate()} days</div>
                        </div>

                        <div className="stat-card">
                            <div className="stat-header">
                                <div className="stat-icon secondary">🎯</div>
                                <span className="stat-label">Top Category</span>
                            </div>
                            <div className="stat-value" style={{ fontSize: '1.75rem' }}>
                                {summary.highest ? summary.highest.icon + ' ' + summary.highest.name : 'None'}
                            </div>
                            <div className="stat-subtitle">
                                {summary.highest ? formatCurrency(summary.highest.total) : 'No expenses yet'}
                            </div>
                        </div>
                    </div>

                    <div className="expense-list">
                        <div className="expense-list-header">
                            <h2>Recent Expenses</h2>
                        </div>

                        {expenses.length === 0 ? (
                            <div className="empty-state">
                                <div className="empty-state-icon">📭</div>
                                <h3>No expenses this month</h3>
                                <p>Start tracking your spending by adding your first expense</p>
                                <button className="btn btn-primary" onClick={onAddClick}>
                                    ➕ Add First Expense
                                </button>
                            </div>
                        ) : (
                            expenses
                                .sort((a, b) => new Date(b.date) - new Date(a.date))
                                .map(expense => {
                                    const category = getCategoryConfig(expense.category);
                                    return (
                                        <div key={expense.id} className="expense-item">
                                            <div className="expense-info">
                                                <div 
                                                    className="expense-category-badge"
                                                    style={{ backgroundColor: category.color + '20', color: category.color }}
                                                >
                                                    {category.icon}
                                                </div>
                                                <div className="expense-details">
                                                    <div className="expense-category-name">{expense.category}</div>
                                                    <div className="expense-meta">
                                                        <span>📅 {formatDate(expense.date)}</span>
                                                    </div>
                                                    {expense.note && (
                                                        <div className="expense-note">"{expense.note}"</div>
                                                    )}
                                                </div>
                                            </div>
                                            <div style={{ display: 'flex', alignItems: 'center', gap: '1rem' }}>
                                                <div className="expense-amount">{formatCurrency(expense.amount)}</div>
                                                <div className="expense-actions">
                                                    <button 
                                                        className="icon-btn"
                                                        onClick={() => onEdit(expense)}
                                                        title="Edit expense"
                                                    >
                                                        ✏️
                                                    </button>
                                                    <button 
                                                        className="icon-btn delete"
                                                        onClick={() => onDelete(expense.id)}
                                                        title="Delete expense"
                                                    >
                                                        🗑️
                                                    </button>
                                                </div>
                                            </div>
                                        </div>
                                    );
                                })
                        )}
                    </div>
                </div>
            );
        }

        // ============================================
        // EXPENSE FORM COMPONENT
        // ============================================
        function ExpenseForm({ onSave, onCancel, editingExpense }) {
            const [formData, setFormData] = useState({
                amount: editingExpense?.amount || '',
                category: editingExpense?.category || 'Food',
                date: editingExpense?.date || new Date().toISOString().split('T')[0],
                note: editingExpense?.note || ''
            });

            const [errors, setErrors] = useState({});

            const validate = () => {
                const newErrors = {};

                if (!formData.amount || parseFloat(formData.amount) <= 0) {
                    newErrors.amount = 'Amount must be greater than 0';
                }

                if (!formData.category) {
                    newErrors.category = 'Please select a category';
                }

                if (!formData.date) {
                    newErrors.date = 'Please select a date';
                }

                setErrors(newErrors);
                return Object.keys(newErrors).length === 0;
            };

            const handleSubmit = (e) => {
                e.preventDefault();
                
                if (validate()) {
                    onSave({
                        amount: parseFloat(formData.amount),
                        category: formData.category,
                        date: formData.date,
                        note: formData.note.trim()
                    });
                }
            };

            return (
                <div className="form-card">
                    <div className="form-header">
                        <h2>{editingExpense ? '✏️ Edit Expense' : '➕ Add New Expense'}</h2>
                        <p>Track your spending to stay on budget</p>
                    </div>

                    <form onSubmit={handleSubmit}>
                        <div className="form-group">
                            <label className="form-label">Amount (₹) *</label>
                            <input
                                type="number"
                                step="0.01"
                                className="form-input"
                                placeholder="0.00"
                                value={formData.amount}
                                onChange={(e) => setFormData({ ...formData, amount: e.target.value })}
                            />
                            {errors.amount && <div className="text-error">{errors.amount}</div>}
                        </div>

                        <div className="form-group">
                            <label className="form-label">Category *</label>
                            <div className="category-grid">
                                {CATEGORIES.map(cat => (
                                    <button
                                        key={cat.name}
                                        type="button"
                                        className={`category-btn ${formData.category === cat.name ? 'active' : ''}`}
                                        style={formData.category === cat.name ? { backgroundColor: cat.color } : {}}
                                        onClick={() => setFormData({ ...formData, category: cat.name })}
                                    >
                                        <span className="category-icon">{cat.icon}</span>
                                        <span>{cat.name}</span>
                                    </button>
                                ))}
                            </div>
                            {errors.category && <div className="text-error">{errors.category}</div>}
                        </div>

                        <div className="form-group">
                            <label className="form-label">Date *</label>
                            <input
                                type="date"
                                className="form-input"
                                value={formData.date}
                                onChange={(e) => setFormData({ ...formData, date: e.target.value })}
                            />
                            {errors.date && <div className="text-error">{errors.date}</div>}
                        </div>

                        <div className="form-group">
                            <label className="form-label">Note (optional)</label>
                            <textarea
                                className="form-textarea"
                                placeholder="What was this expense for?"
                                value={formData.note}
                                onChange={(e) => setFormData({ ...formData, note: e.target.value })}
                            />
                        </div>

                        <div className="btn-group">
                            <button type="submit" className="btn btn-primary">
                                {editingExpense ? '💾 Update Expense' : '➕ Add Expense'}
                            </button>
                            {editingExpense && (
                                <button type="button" className="btn btn-secondary" onClick={onCancel}>
                                    ✖️ Cancel
                                </button>
                            )}
                        </div>
                    </form>
                </div>
            );
        }

        // ============================================
        // SUMMARY COMPONENT
        // ============================================
        function Summary({ summary, expenses, selectedMonth, selectedYear, onMonthChange }) {
            const pieChartRef = useRef(null);
            const barChartRef = useRef(null);
            const lineChartRef = useRef(null);
            const pieChartInstance = useRef(null);
            const barChartInstance = useRef(null);
            const lineChartInstance = useRef(null);

            // Get daily data for bar chart
            const getDailyData = () => {
                const monthExpenses = expenses.filter(exp => {
                    const expDate = new Date(exp.date);
                    return expDate.getMonth() === selectedMonth && expDate.getFullYear() === selectedYear;
                });

                const dailyTotals = {};
                monthExpenses.forEach(exp => {
                    const day = new Date(exp.date).getDate();
                    dailyTotals[day] = (dailyTotals[day] || 0) + exp.amount;
                });

                return Object.entries(dailyTotals)
                    .map(([day, amount]) => ({ day: parseInt(day), amount }))
                    .sort((a, b) => a.day - b.day);
            };

            // Get monthly comparison data
            const getMonthlyData = () => {
                const monthlyTotals = {};

                expenses.forEach(exp => {
                    const date = new Date(exp.date);
                    const key = `${date.getFullYear()}-${date.getMonth()}`;
                    const label = `${getMonthName(date.getMonth()).slice(0, 3)} ${date.getFullYear()}`;

                    if (!monthlyTotals[key]) {
                        monthlyTotals[key] = { month: label, amount: 0, sortKey: key };
                    }
                    monthlyTotals[key].amount += exp.amount;
                });

                return Object.values(monthlyTotals)
                    .sort((a, b) => a.sortKey.localeCompare(b.sortKey))
                    .slice(-6); // Last 6 months
            };

            // Render charts
            useEffect(() => {
                // Pie Chart
                if (pieChartRef.current && summary.byCategory.length > 0) {
                    if (pieChartInstance.current) {
                        pieChartInstance.current.destroy();
                    }

                    const ctx = pieChartRef.current.getContext('2d');
                    pieChartInstance.current = new Chart(ctx, {
                        type: 'pie',
                        data: {
                            labels: summary.byCategory.map(cat => cat.name),
                            datasets: [{
                                data: summary.byCategory.map(cat => cat.total),
                                backgroundColor: summary.byCategory.map(cat => cat.color),
                                borderWidth: 2,
                                borderColor: '#fff'
                            }]
                        },
                        options: {
                            responsive: true,
                            maintainAspectRatio: false,
                            plugins: {
                                legend: {
                                    position: 'bottom',
                                    labels: {
                                        padding: 15,
                                        font: {
                                            size: 12,
                                            family: 'Manrope'
                                        }
                                    }
                                },
                                tooltip: {
                                    callbacks: {
                                        label: function(context) {
                                            return context.label + ': ' + formatCurrency(context.parsed);
                                        }
                                    }
                                }
                            }
                        }
                    });
                }

                // Bar Chart
                const dailyData = getDailyData();
                if (barChartRef.current && dailyData.length > 0) {
                    if (barChartInstance.current) {
                        barChartInstance.current.destroy();
                    }

                    const ctx = barChartRef.current.getContext('2d');
                    barChartInstance.current = new Chart(ctx, {
                        type: 'bar',
                        data: {
                            labels: dailyData.map(d => d.day),
                            datasets: [{
                                label: 'Daily Spending',
                                data: dailyData.map(d => d.amount),
                                backgroundColor: 'rgba(16, 185, 129, 0.6)',
                                borderColor: 'rgb(16, 185, 129)',
                                borderWidth: 2,
                                borderRadius: 8
                            }]
                        },
                        options: {
                            responsive: true,
                            maintainAspectRatio: false,
                            plugins: {
                                legend: {
                                    display: false
                                },
                                tooltip: {
                                    callbacks: {
                                        label: function(context) {
                                            return 'Amount: ' + formatCurrency(context.parsed.y);
                                        }
                                    }
                                }
                            },
                            scales: {
                                y: {
                                    beginAtZero: true,
                                    ticks: {
                                        callback: function(value) {
                                            return '₹' + value;
                                        }
                                    }
                                },
                                x: {
                                    title: {
                                        display: true,
                                        text: 'Day of Month'
                                    }
                                }
                            }
                        }
                    });
                }

                // Line Chart
                const monthlyData = getMonthlyData();
                if (lineChartRef.current && monthlyData.length > 1) {
                    if (lineChartInstance.current) {
                        lineChartInstance.current.destroy();
                    }

                    const ctx = lineChartRef.current.getContext('2d');
                    lineChartInstance.current = new Chart(ctx, {
                        type: 'line',
                        data: {
                            labels: monthlyData.map(d => d.month),
                            datasets: [{
                                label: 'Monthly Spending',
                                data: monthlyData.map(d => d.amount),
                                borderColor: 'rgb(16, 185, 129)',
                                backgroundColor: 'rgba(16, 185, 129, 0.1)',
                                borderWidth: 3,
                                tension: 0.4,
                                fill: true,
                                pointRadius: 5,
                                pointBackgroundColor: 'rgb(16, 185, 129)'
                            }]
                        },
                        options: {
                            responsive: true,
                            maintainAspectRatio: false,
                            plugins: {
                                legend: {
                                    display: false
                                },
                                tooltip: {
                                    callbacks: {
                                        label: function(context) {
                                            return 'Total
