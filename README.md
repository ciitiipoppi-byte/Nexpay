<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NexPay - Make Money Online Worldwide</title>
    <meta name="description" content="Join NexPay for $100, get $50 signup bonus, and start earning by completing tasks and referrals from anywhere.">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            line-height: 1.6;
            color: #333;
        }
        header {
            background-color: #1a73e8;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #f4f4f4;
            padding: 1rem;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }
        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        nav a:hover {
            color: #1a73e8;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1542744173-05336fcc7ad4') center/cover;
            padding: 4rem 1rem;
            text-align: center;
            color: white;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .cta-button {
            background-color: #28a745;
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            border: none;
        }
        .cta-button:hover {
            background-color: #218838;
        }
        .tasks, .how-it-works, .win-items {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .tasks h2, .how-it-works h2, .win-items h2 {
            text-align: center;
            margin-bottom: 2rem;
            color: #1a73e8;
        }
        .task-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        .task-card {
            background-color: #f9f9f9;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .task-card h3 {
            margin-bottom: 1rem;
        }
        .task-card p {
            color: #555;
        }
        .steps {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .step {
            flex: 1;
            min-width: 200px;
            text-align: center;
            padding: 1rem;
        }
        .step h3 {
            margin-bottom: 0.5rem;
        }
        /* Win Items Section */
        .win-items {
            position: relative;
            text-align: center;
        }
        .win-items img {
            width: 100%;
            max-width: 800px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        .win-items .overlay-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 1rem 2rem;
            border-radius: 8px;
            font-size: 1.2rem;
            font-weight: bold;
            text-align: center;
            max-width: 80%;
            white-space: normal; /* Allows natural text flow without shifting */
        }
        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            justify-content: center;
            align-items: center;
        }
        .modal-content {
            background-color: white;
            padding: 2rem;
            border-radius: 8px;
            text-align: center;
            max-width: 400px;
            width: 90%;
        }
        .modal-content h3 {
            margin-bottom: 1rem;
        }
        .modal-content p {
            margin-bottom: 1rem;
        }
        .modal-content .wallet-address, .modal-content .support-link {
            word-break: break-all; /* Ensures wallet address and email fit */
            font-size: 0.9rem;
        }
        .modal-content .no-wrap {
            white-space: nowrap; /* Prevents wrapping for other text */
            font-size: 1rem;
        }
        .close-button {
            background-color: #ff4444;
            color: white;
            padding: 0.5rem 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .close-button:hover {
            background-color: #cc0000;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 1.8rem;
            }
            .hero p {
                font-size: 1rem;
            }
            nav ul {
                flex-direction: column;
                gap: 1rem;
            }
            .win-items .overlay-text {
                font-size: 1rem;
                padding: 0.8rem 1.5rem;
            }
            .modal-content .no-wrap {
                font-size: 0.9rem; /* Slightly smaller for mobile */
            }
            .modal-content .wallet-address, .modal-content .support-link {
                font-size: 0.8rem; /* Smaller for mobile to ensure fit */
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>NexPay</h1>
        <p>Your No. 1 Platform to Earn Money Online Worldwide</p>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#tasks">Tasks</a></li>
            <li><a href="#how-it-works">How It Works</a></li>
            <li><a href="#register">Register</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Earn $1,000+ Monthly + $50 Signup Bonus</h1>
        <p>Join NexPay for $100, get $50 instantly, and earn $20 daily logins, $10 per referral, and more!</p>
        <a href="#register" class="cta-button">Get Started Now</a>
    </section>

    <!-- Tasks Section -->
    <section class="tasks" id="tasks">
        <h2>Explore Earning Opportunities</h2>
        <div class="task-grid">
            <div class="task-card">
                <h3>Signup Bonus</h3>
                <p>Get $50 instantly upon registering.</p>
            </div>
            <div class="task-card">
                <h3>Daily Logins</h3>
                <p>Login daily and earn $20 .</p>
            </div>
            <div class="task-card">
                <h3>Affiliate Marketing</h3>
                <p>Promote products and earn commissions up to 30%.</p>
            </div>
            <div class="task-card">
                <h3>Refer & Earn</h3>
                <p>Invite friends to join and earn $10 per referral after registration.</p>
            </div>
               <div class="task-card">
<h3>Nexpay Gift Box</h3>
<p>Register and get Nexpay GiftBox containing phones and Accessories For your daily task.</p>
</div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="how-it-works" id="how-it-works">
        <h2>How It Works</h2>
        <div class="steps">
            <div class="step">
                <h3>1. Register & Deposit</h3>
                <p>Send $100 USDT (ERC20) to our wallet to unlock earnings and get $50 bonus.</p>
            </div>
            <div class="step">
                <h3>2. Complete Activities</h3>
                <p>Log in daily for $20, refer friends for $10, or do tasks to earn instantly.</p>
            </div>
            <div class="step">
                <h3>3. Withdraw Earnings</h3>
                <p>Cash out to your crypto wallet from $100 minimum.</p>
            </div>
        </div>
    </section>
        
    </section>

    <!-- Call to Action / Registration -->
    <section class="hero" id="register">
        <h1>Start Earning with NexPay!</h1>
        <p>Join thousands earning online. Send $100 USDT (ERC20) to our wallet to unlock your dashboard and get $50 bonus.</p>
        <button class="cta-button" onclick="openModal()">Register</button>
    </section>

    <!-- Modal for Payment Details -->
    <div id="paymentModal" class="modal">
        <div class="modal-content">
            <h3>Payment Details</h3>
            <p class="no-wrap"><strong>Network:</strong> USDT ERC20</p>
            <p><strong>Wallet Address:</strong> <span class="wallet-address">0xEEDb29F88dA69a676A864b6AF327Ec3ad172cbDA</span></p>
            <p class="no-wrap">Send exactly $100 USDT and contact <a href="mailto:support@nexpay.com" class="support-link">support@nexpay.com</a> </p>
            <button class="close-button" onclick="closeModal()">Close</button>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 NexPay Global. All rights reserved.</p>
        <p>Contact: support@nexpay.com
         <p>  𝗜𝗻 𝗖𝗼-𝗼𝗽𝗲𝗿𝗮𝘁𝗶𝗼𝗻 𝘄𝗶𝘁𝗵 
        𝗠𝗲𝘁𝗮</p>
    </footer>

    <!-- JavaScript for Modal -->
    <script>
        function openModal() {
            document.getElementById('paymentModal').style.display = 'flex';
        }
        function closeModal() {
            document.getElementById('paymentModal').style.display = 'none';
        }
    </script>
</body>
</html>
