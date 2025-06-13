<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Ultimate Real Estate Sales Script Training Guide</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fff;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #2c5aa0 0%, #1e3d6f 100%);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            font-weight: bold;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero .subheadline {
            font-size: 1.4rem;
            margin-bottom: 30px;
            color: #e8f4ff;
        }
        
        .book-visual {
            margin: 40px 0;
        }
        
        .book-cover {
            width: 300px;
            height: 400px;
            background: linear-gradient(145deg, #ffffff, #f0f0f0);
            border-radius: 10px;
            box-shadow: 0 15px 30px rgba(0,0,0,0.3);
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #2c5aa0;
            padding: 30px;
        }
        
        .book-cover h3 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            font-weight: bold;
        }
        
        .book-cover p {
            font-size: 1rem;
            line-height: 1.4;
        }
        
        .cta-button {
            background: #ff6b35;
            color: white;
            padding: 20px 40px;
            font-size: 1.3rem;
            font-weight: bold;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            box-shadow: 0 8px 15px rgba(255, 107, 53, 0.3);
        }
        
        .cta-button:hover {
            background: #e55a2b;
            transform: translateY(-2px);
            box-shadow: 0 12px 20px rgba(255, 107, 53, 0.4);
        }
        
        /* Benefits Section */
        .benefits {
            padding: 80px 0;
            background: #f8f9fa;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #2c5aa0;
        }
        
        .section-subtitle {
            text-align: center;
            font-size: 1.2rem;
            margin-bottom: 50px;
            color: #666;
        }
        
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .benefit-item {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .benefit-icon {
            width: 60px;
            height: 60px;
            background: #2c5aa0;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            color: white;
            font-size: 1.5rem;
        }
        
        .benefit-item h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: #2c5aa0;
        }
        
        /* Social Proof Section */
        .social-proof {
            padding: 80px 0;
            background: white;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .testimonial {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 10px;
            border-left: 5px solid #2c5aa0;
        }
        
        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            font-size: 1.1rem;
        }
        
        .testimonial-author {
            font-weight: bold;
            color: #2c5aa0;
        }
        
        /* Preview Section */
        .preview {
            padding: 80px 0;
            background: #2c5aa0;
            color: white;
        }
        
        .preview-content {
            background: rgba(255,255,255,0.1);
            padding: 40px;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        .preview h3 {
            color: #ff6b35;
            margin-bottom: 20px;
        }
        
        /* Urgency Section */
        .urgency {
            padding: 60px 0;
            background: #ff6b35;
            color: white;
            text-align: center;
        }
        
        .countdown {
            font-size: 2rem;
            font-weight: bold;
            margin: 20px 0;
        }
        
        /* FAQ Section */
        .faq {
            padding: 80px 0;
            background: #f8f9fa;
        }
        
        .faq-item {
            background: white;
            margin-bottom: 20px;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .faq-question {
            background: #2c5aa0;
            color: white;
            padding: 20px;
            cursor: pointer;
            font-weight: bold;
        }
        
        .faq-answer {
            padding: 20px;
            background: white;
        }
        
        /* Footer CTA */
        .footer-cta {
            padding: 80px 0;
            background: #1e3d6f;
            color: white;
            text-align: center;
        }
        
        .guarantee {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero .subheadline {
                font-size: 1.2rem;
            }
            
            .book-cover {
                width: 250px;
                height: 330px;
            }
            
            .benefits-grid {
                grid-template-columns: 1fr;
            }
            
            .testimonial-grid {
                grid-template-columns: 1fr;
            }
        }
        
        .highlight {
            background: #fff3cd;
            padding: 2px 8px;
            border-radius: 4px;
            color: #856404;
        }
        
        .price {
            font-size: 2.5rem;
            font-weight: bold;
            color: #ff6b35;
        }
        
        .old-price {
            text-decoration: line-through;
            color: #999;
            font-size: 1.5rem;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Master the Scripts That Close Your First Real Estate Deal</h1>
            <p class="subheadline">Step-by-step sales scripts to build confidence, overcome objections, and win clients in your first year</p>
            
            <div class="book-visual">
                <div class="book-cover">
                    <h3>The Ultimate Real Estate Sales Script Training Guide</h3>
                    <p>31 Chapters of Proven Scripts, Objection Handling, and Closing Techniques</p>
                </div>
            </div>
            
            <a class="gumroad-button cta-button" href="https://ryanfarm.gumroad.com/l/cvgdm" target="_blank" data-gumroad-single-product="true">Get My Copy & Start Closing Deals</a>
            
            <p style="margin-top: 20px; font-size: 1rem;">✅ Instant Download • ✅ 30-Day Money-Back Guarantee • ✅ Used by 2,000+ Agents</p>
        </div>
    </section>

    <!-- Benefits Section -->
    <section class="benefits">
        <div class="container">
            <h2 class="section-title">Stop Fumbling for Words. Start Closing Deals.</h2>
            <p class="section-subtitle">Every conversation becomes an opportunity when you know exactly what to say</p>
            
            <div class="benefits-grid">
                <div class="benefit-item">
                    <div class="benefit-icon">📞</div>
                    <h3>Master Cold Calling</h3>
                    <p>Turn "not interested" into appointments with proven phone scripts that actually work. Stop dreading cold calls and start booking meetings.</p>
                </div>
                
                <div class="benefit-item">
                    <div class="benefit-icon">🏠</div>
                    <h3>Win Listing Presentations</h3>
                    <p>Walk into every seller meeting with confidence. Our step-by-step listing scripts help you compete against experienced agents and win.</p>
                </div>
                
                <div class="benefit-item">
                    <div class="benefit-icon">💰</div>
                    <h3>Close More Buyers</h3>
                    <p>Guide hesitant buyers to confident decisions with proven closing techniques. Stop losing deals to indecision and start earning commissions.</p>
                </div>
                
                <div class="benefit-item">
                    <div class="benefit-icon">🛡️</div>
                    <h3>Handle Any Objection</h3>
                    <p>Never get stumped again. Complete objection-handling scripts for every situation from "I need to think about it" to "Your commission is too high."</p>
                </div>
                
                <div class="benefit-item">
                    <div class="benefit-icon">📈</div>
                    <h3>Follow-Up Like a Pro</h3>
                    <p>Turn "maybes" into "yeses" with systematic follow-up strategies. Most deals close after the 5th contact - be the agent who follows up.</p>
                </div>
                
                <div class="benefit-item">
                    <div class="benefit-icon">🎯</div>
                    <h3>Build Instant Rapport</h3>
                    <p>Connect with any client in minutes using proven rapport-building techniques. People buy from agents they know, like, and trust.</p>
                </div>
            </div>
            
            <div style="text-align: center;">
                <a class="gumroad-button cta-button" href="https://ryanfarm.gumroad.com/l/cvgdm" target="_blank" data-gumroad-single-product="true">Yes, I Want These Scripts Now</a>
            </div>
        </div>
    </section>

    <!-- Social Proof Section -->
    <section class="social-proof">
        <div class="container">
            <h2 class="section-title">Real Agents. Real Results.</h2>
            <p class="section-subtitle">Join the 2,000+ agents already using these scripts to transform their careers</p>
            
            <div class="testimonial-grid">
                <div class="testimonial">
                    <p class="testimonial-text">"I was nervous about my first listing presentation, but these scripts gave me the confidence I needed. I got the listing and it sold in 10 days! The commission from that one deal paid for the book 50 times over."</p>
                    <p class="testimonial-author">— Sarah M., New Agent, Toronto</p>
                </div>
                
                <div class="testimonial">
                    <p class="testimonial-text">"The cold calling scripts are gold. I went from dreading phone calls to booking 3-4 appointments per week. My manager noticed my confidence immediately."</p>
                    <p class="testimonial-author">— Mike R., 6 months experience, Vancouver</p>
                </div>
                
                <div class="testimonial">
                    <p class="testimonial-text">"Before this book, I was losing deals to more experienced agents. Now I have scripts for every situation and my closing rate has doubled. Best investment I've made in my career."</p>
                    <p class="testimonial-author">— Jennifer L., First-year agent, Calgary</p>
                </div>
            </div>
            
            <div style="text-align: center; background: #e8f4ff; padding: 30px; border-radius: 10px;">
                <h3 style="color: #2c5aa0; margin-bottom: 15px;">Written by a Top 1% Producer</h3>
                <p style="font-size: 1.1rem;">With 20+ years in real estate and over $500M in career sales, the author has trained thousands of agents using these exact scripts. You're learning from someone who's been in your shoes and achieved massive success.</p>
            </div>
        </div>
    </section>

    <!-- Preview Section -->
    <section class="preview">
        <div class="container">
            <h2 class="section-title" style="color: white;">Sneak Peek: What's Inside</h2>
            <p class="section-subtitle" style="color: #e8f4ff;">Here's a sample from Chapter 4: Cold Calling Scripts</p>
            
            <div class="preview-content">
                <h3>Expired Listing Script:</h3>
                <p style="font-size: 1.1rem; line-height: 1.8;">
                    <strong>Agent:</strong> "Hi [Seller's Name], I noticed your home was on the market but didn't sell. I specialize in helping sellers in this exact situation. What was your experience with your last agent?"<br><br>
                    
                    <strong>Seller:</strong> "We didn't get enough offers, so we decided to wait."<br><br>
                    
                    <strong>Agent:</strong> "I understand that's frustrating. The good news is there are specific strategies to generate more buyer interest. Would you be open to a quick conversation about what might work differently this time?"<br><br>
                    
                    <em>➡ Why This Works: Acknowledges their pain, positions you as the solution, and uses a soft close to book the appointment.</em>
                </p>
            </div>
            
            <div style="text-align: center;">
                <p style="font-size: 1.2rem; margin-bottom: 20px;">This is just 1 script from 200+ included in the book</p>
                <a class="gumroad-button cta-button" href="https://ryanfarm.gumroad.com/l/cvgdm" target="_blank" data-gumroad-single-product="true">Get All 200+ Scripts Now</a>
            </div>
        </div>
    </section>

    <!-- Urgency Section -->
    <section class="urgency">
        <div class="container">
            <h2 style="font-size: 2.5rem; margin-bottom: 20px;">⚠️ Don't Wait - Every Day Costs You Commissions</h2>
            <p style="font-size: 1.3rem; margin-bottom: 20px;">While you're thinking about it, other agents are using these scripts to win the deals you could be closing</p>
            
            <div style="background: rgba(255,255,255,0.2); padding: 30px; border-radius: 10px; margin: 30px 0;">
                <h3 style="font-size: 1.5rem; margin-bottom: 15px;">🔥 Launch Week Special - 50% OFF</h3>
                <p class="countdown">Offer expires in 3 days!</p>
                <p style="font-size: 1.1rem;">Join the first 500 agents to get instant access</p>
            </div>
            
            <a class="gumroad-button cta-button" href="https://ryanfarm.gumroad.com/l/cvgdm" target="_blank" data-gumroad-single-product="true" style="background: white; color: #ff6b35;">Secure My Copy Before Price Increases</a>
        </div>
    </section>

    <!-- What You'll Learn Section -->
    <section style="padding: 80px 0; background: white;">
        <div class="container">
            <h2 class="section-title">Complete Training System: 31 Chapters Covering Everything</h2>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-top: 40px;">
                <div style="background: #f8f9fa; padding: 20px; border-radius: 10px;">
                    <h4 style="color: #2c5aa0; margin-bottom: 10px;">📞 Mastering Phone Skills</h4>
                    <ul style="line-height: 2;">
                        <li>Cold calling frameworks that book appointments</li>
                        <li>Warm calling scripts for online leads</li>
                        <li>Follow-up sequences that convert</li>
                    </ul>
                </div>
                
                <div style="background: #f8f9fa; padding: 20px; border-radius: 10px;">
                    <h4 style="color: #2c5aa0; margin-bottom: 10px;">🏠 Winning Listings</h4>
                    <ul style="line-height: 2;">
                        <li>Listing presentation scripts</li>
                        <li>Pricing objection handling</li>
                        <li>Competitive advantage positioning</li>
                    </ul>
                </div>
                
                <div style="background: #f8f9fa; padding: 20px; border-radius: 10px;">
                    <h4 style="color: #2c5aa0; margin-bottom: 10px;">💼 Buyer Consultation</h4>
                    <ul style="line-height: 2;">
                        <li>First-time buyer guidance scripts</li>
                        <li>Showing property techniques</li>
                        <li>Closing and negotiation strategies</li>
                    </ul>
                </div>
                
                <div style="background: #f8f9fa; padding: 20px; border-radius: 10px;">
                    <h4 style="color: #2c5aa0; margin-bottom: 10px;">🚫 Objection Mastery</h4>
                    <ul style="line-height: 2;">
                        <li>"I need to think about it" responses</li>
                        <li>Commission objection handling</li>
                        <li>Market timing concerns</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="faq">
        <div class="container">
            <h2 class="section-title">Frequently Asked Questions</h2>
            
            <div class="faq-item">
                <div class="faq-question">Q: I'm brand new - will this help if I have zero sales experience?</div>
                <div class="faq-answer">A: Absolutely! This book is specifically designed for new agents. Every script includes step-by-step instructions and explains WHY it works, so you'll understand the psychology behind successful sales conversations.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: What format is the book available in?</div>
                <div class="faq-answer">A: You'll get instant access to both PDF download and online access portal. Read on any device - phone, tablet, computer, or print it out for easy reference.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: Does this cover both residential and commercial?</div>
                <div class="faq-answer">A: The focus is on residential real estate, which is where 90% of new agents start. The principles and scripts work for any real estate transaction.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: What if I don't like the book or it doesn't help?</div>
                <div class="faq-answer">A: We offer a 30-day money-back guarantee. If you're not completely satisfied, just email us for a full refund. No questions asked.</div>
            </div>
        </div>
    </section>

    <!-- Final CTA Section -->
    <section class="footer-cta" id="order">
        <div class="container">
            <h2 style="font-size: 2.5rem; margin-bottom: 20px;">Ready to Transform Your Real Estate Career?</h2>
            <p style="font-size: 1.3rem; margin-bottom: 30px;">Join 2,000+ agents who've already mastered these scripts</p>
            
            <div class="guarantee">
                <h3 style="margin-bottom: 15px;">🛡️ Iron-Clad 30-Day Guarantee</h3>
                <p>Use these scripts for 30 days. If you don't feel more confident in your sales conversations and start seeing better results, we'll refund every penny. You have nothing to lose and everything to gain.</p>
            </div>
            
            <div style="background: rgba(255,255,255,0.1); padding: 40px; border-radius: 10px; margin-bottom: 30px;">
                <h3 style="margin-bottom: 20px;">Special Launch Pricing:</h3>
                <p style="margin-bottom: 10px;"><span class="old-price">$197</span> <span class="price">$97</span></p>
                <p style="font-size: 1.1rem; margin-bottom: 20px;">Save $100 - Launch week only!</p>
                <p><strong>What you get:</strong></p>
                <ul style="text-align: left; display: inline-block; margin-top: 15px;">
                    <li>✅ 200+ Proven Scripts & Dialogues</li>
                    <li>✅ 31 Comprehensive Chapters</li>
                    <li>✅ Objection Handling Mastery</li>
                    <li>✅ Follow-up Systems That Work</li>
                    <li>✅ Instant Download Access</li>
                    <li>✅ Mobile-Friendly Format</li>
                    <li>✅ 30-Day Money-Back Guarantee</li>
                </ul>
            </div>
            
            <a class="gumroad-button cta-button" href="https://ryanfarm.gumroad.com/l/cvgdm" target="_blank" data-gumroad-single-product="true" style="font-size: 1.5rem; padding: 25px 50px;">Get Instant Access - $97</a>
            
            <p style="margin-top: 20px; font-size: 0.9rem;">🔒 Secure Checkout • 💳 All Major Cards Accepted • 📱 Instant Digital Delivery</p>
            
            <div style="margin-top: 40px; font-size: 0.9rem; color: #ccc;">
                <p>Remember: Every month without these scripts is a missed commission opportunity. The average real estate agent earns $48,000 annually. Top agents using proven scripts earn $250,000+. Which agent do you want to be?</p>
            </div>
        </div>
    </section>

    <!-- Gumroad Integration Script -->
    <script src="https://gumroad.com/js/gumroad.js"></script>
    
    <script>
        // Simple FAQ toggle functionality
        document.querySelectorAll('.faq-question').forEach(question => {
            question.addEventListener('click', () => {
                const answer = question.nextElementSibling;
                answer.style.display = answer.style.display === 'none' || answer.style.display === '' ? 'block' : 'none';
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
