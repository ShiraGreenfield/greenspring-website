---
layout: page
permalink: /contact/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Green Spring Mental Health</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f8fffe 0%, #e8f5f0 100%);
            min-height: 100vh;
            padding: 20px;
            color: #2c5530;
        }

        .form-container {
            max-width: 600px;
            margin: 40px auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(76, 130, 89, 0.1);
            overflow: hidden;
            position: relative;
        }

        .form-header {
            background: linear-gradient(135deg, #6b9c7a 0%, #4a7c59 100%);
            color: white;
            padding: 40px 30px;
            text-align: center;
            position: relative;
        }

        .form-header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 1px, transparent 1px);
            background-size: 20px 20px;
            animation: drift 20s infinite linear;
        }

        @keyframes drift {
            0% { transform: translateX(0) translateY(0); }
            100% { transform: translateX(20px) translateY(20px); }
        }

        .form-header h1 {
            font-size: 28px;
            margin-bottom: 10px;
            font-weight: 300;
            position: relative;
            z-index: 1;
        }

        .form-header p {
            font-size: 16px;
            opacity: 0.9;
            position: relative;
            z-index: 1;
        }

        .form-content {
            padding: 40px 30px;
        }

        .form-group {
            margin-bottom: 25px;
            position: relative;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #2c5530;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        input[type="email"], textarea {
            width: 100%;
            padding: 16px 20px;
            border: 2px solid #e8f1ea;
            border-radius: 12px;
            font-size: 16px;
            background: #f9fcfa;
            transition: all 0.3s ease;
            font-family: inherit;
            color: #2c5530;
        }

        input[type="email"]:focus, textarea:focus {
            outline: none;
            border-color: #6b9c7a;
            background: white;
            box-shadow: 0 0 0 4px rgba(107, 156, 122, 0.1);
            transform: translateY(-2px);
        }

        textarea {
            resize: vertical;
            min-height: 120px;
            line-height: 1.6;
        }

        .submit-btn {
            width: 100%;
            padding: 18px;
            background: linear-gradient(135deg, #6b9c7a 0%, #4a7c59 100%);
            color: white;
            border: none;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
            overflow: hidden;
        }

        .submit-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s;
        }

        .submit-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(107, 156, 122, 0.3);
        }

        .submit-btn:hover::before {
            left: 100%;
        }

        .submit-btn:active {
            transform: translateY(-1px);
        }

        .form-footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #e8f1ea;
            font-size: 14px;
            color: #6b9c7a;
        }

        .floating-elements {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }

        .floating-leaf {
            position: absolute;
            opacity: 0.1;
            font-size: 20px;
            color: #6b9c7a;
            animation: float 6s ease-in-out infinite;
        }

        .floating-leaf:nth-child(1) {
            top: 20%;
            left: 10%;
            animation-delay: 0s;
        }

        .floating-leaf:nth-child(2) {
            top: 60%;
            right: 15%;
            animation-delay: 2s;
        }

        .floating-leaf:nth-child(3) {
            bottom: 30%;
            left: 20%;
            animation-delay: 4s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }

        @media (max-width: 768px) {
            .form-container {
                margin: 20px auto;
                border-radius: 15px;
            }
            
            .form-content {
                padding: 30px 20px;
            }
            
            .form-header {
                padding: 30px 20px;
            }
            
            .form-header h1 {
                font-size: 24px;
            }
        }

        /* Custom focus indicator for accessibility */
        input[type="email"]:focus-visible, 
        textarea:focus-visible, 
        .submit-btn:focus-visible {
            outline: 3px solid #6b9c7a;
            outline-offset: 2px;
        }
    </style>
</head>
<body>
    <div class="floating-elements">
        <div class="floating-leaf">🌿</div>
        <div class="floating-leaf">🍃</div>
        <div class="floating-leaf">🌱</div>
    </div>

    <div class="form-container">
        <div class="form-header">
            <h1 style="font-weight: bold">Get in Touch</h1>
            <p>We're here to support your mental health journey</p>
        </div>
        
        <div class="form-content">
            <form action="https://formspree.io/f/mdkzbwzd" method="POST">
                <div class="form-group">
                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" required placeholder="Enter your email address">
                </div>
                
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea id="message" name="message" required placeholder="Share what's on your mind or ask any questions you may have..."></textarea>
                </div>
                
                <button type="submit" class="submit-btn">Send Message</button>
                

            </form>
        </div>
    </div>

    <script>
        // Add smooth form interactions
        document.addEventListener('DOMContentLoaded', function() {
            const inputs = document.querySelectorAll('input, textarea');
            
            inputs.forEach(input => {
                input.addEventListener('focus', function() {
                    this.parentElement.style.transform = 'scale(1.02)';
                });
                
                input.addEventListener('blur', function() {
                    this.parentElement.style.transform = 'scale(1)';
                });
            });

            // Form submission feedback
            const form = document.querySelector('form');
            const submitBtn = document.querySelector('.submit-btn');
            
            form.addEventListener('submit', function() {
                submitBtn.innerHTML = 'Sending...';
                submitBtn.style.background = 'linear-gradient(135deg, #5a8569 0%, #3f6b4e 100%)';
            });
        });
    </script>
</body>
</html>