<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gilthead Seabream Slaughter Study Canvas</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #333;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
            color: white;
            font-size: 2.5rem;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .canvas-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 25px;
            margin-bottom: 30px;
        }

        .canvas-section {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid rgba(255,255,255,0.3);
        }

        .canvas-section:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        }

        .section-title {
            font-size: 1.4rem;
            font-weight: bold;
            margin-bottom: 15px;
            color: #2c3e50;
            border-bottom: 3px solid #3498db;
            padding-bottom: 8px;
        }

        .section-content {
            line-height: 1.6;
            font-size: 0.95rem;
        }

        .highlight-box {
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
            padding: 15px;
            border-radius: 10px;
            margin: 15px 0;
            border-left: 4px solid #e74c3c;
        }

        .method-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 10px;
            margin: 15px 0;
        }

        .method-item {
            background: #ecf0f1;
            padding: 10px;
            border-radius: 8px;
            text-align: center;
            font-weight: bold;
            color: #2c3e50;
        }

        .electrical { background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%); }
        .anaesthesia { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); }
        .no-stunning { background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%); }
        .ice-slurry { background: linear-gradient(135deg, #74b9ff 0%, #0984e3 100%); color: white; }
        .ikejime { background: linear-gradient(135deg, #fd79a8 0%, #fdcb6e 100%); }

        .results-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 15px 0;
        }

        .result-card {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            border-left: 4px solid #27ae60;
        }

        .stat-number {
            font-size: 1.8rem;
            font-weight: bold;
            color: #e74c3c;
        }

        .implications-list {
            list-style: none;
            padding: 0;
        }

        .implications-list li {
            background: #e8f5e8;
            margin: 8px 0;
            padding: 12px;
            border-radius: 8px;
            border-left: 4px solid #27ae60;
            position: relative;
        }

        .implications-list li:before {
            content: "→";
            position: absolute;
            left: -5px;
            color: #27ae60;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .future-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin: 15px 0;
        }

        .future-item {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
        }

        .methodology-flow {
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            margin: 20px 0;
        }

        .flow-step {
            background: #3498db;
            color: white;
            padding: 15px;
            border-radius: 50%;
            width: 80px;
            height: 80px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin: 10px;
        }

        .arrow {
            font-size: 2rem;
            color: #3498db;
            margin: 0 10px;
        }

        @media (max-width: 768px) {
            .canvas-grid {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .methodology-flow {
                flex-direction: column;
            }
            
            .arrow {
                transform: rotate(90deg);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Stunning and slaughter methods in gilthead seabream: Animal welfare and muscle quality</h1>
        <div style="text-align: center; color: rgba(255,255,255,0.9); font-size: 1.1rem; margin-bottom: 30px; font-style: italic;">
            María J. Cabrera-Álvarez, Sónia Marina António Soares, Samira Nuñez-Velazquez, Jaime Aníbal, Eduardo Esteves, Rita A. Costa, Pedro M. Guerreiro, Pedro Pousão-Ferreira, Pablo Arechavala-López, João L. Saraiva
        </div>
        
        <div class="canvas-grid">
            <!-- Study Overview -->
            <div class="canvas-section">
                <div class="section-title">📋 Study Overview</div>
                <div class="section-content">
                    <p><strong>Objective:</strong> Assess the impact of diverse combinations of stunning and slaughter techniques on welfare indicators and quality parameters of gilthead seabream.</p>
                    
                    <div class="highlight-box">
                        <strong>Key Focus:</strong> Comparison of electrical stunning, anaesthesia, and no stunning, each followed by either ice-slurry immersion or ikejime technique.
                    </div>
                    
                    <p><strong>Sample Size:</strong> 32 adult gilthead seabream (mean body weight: 923.1 ± 25.8 g)</p>
                    <p><strong>Duration:</strong> 3 consecutive days with randomized treatment application</p>
                </div>
            </div>

            <!-- Methodology -->
            <div class="canvas-section">
                <div class="section-title">🔬 Methodology</div>
                <div class="section-content">
                    <div class="methodology-flow">
                        <div class="flow-step">Bio-logger Implant</div>
                        <span class="arrow">→</span>
                        <div class="flow-step">Recovery Period</div>
                        <span class="arrow">→</span>
                        <div class="flow-step">Treatment Application</div>
                        <span class="arrow">→</span>
                        <div class="flow-step">Data Collection</div>
                    </div>
                    
                    <div class="method-grid">
                        <div class="method-item electrical">Electrical Stunning</div>
                        <div class="method-item anaesthesia">Anaesthesia</div>
                        <div class="method-item no-stunning">No Stunning</div>
                        <div class="method-item ice-slurry">Ice-Slurry</div>
                        <div class="method-item ikejime">Ikejime</div>
                    </div>
                    
                    <p><strong>Measurements:</strong> Visual consciousness indicators, heart rate, internal temperature, blood parameters, and muscle quality metrics.</p>
                </div>
            </div>

            <!-- Key Results -->
            <div class="canvas-section">
                <div class="section-title">📊 Key Results</div>
                <div class="section-content">
                    <div class="results-grid">
                        <div class="result-card">
                            <div class="stat-number">18±3 min</div>
                            <p>Time to death in ice-slurry without stunning</p>
                        </div>
                        <div class="result-card">
                            <div class="stat-number">136±107 s</div>
                            <p>Average ikejime time without stunning</p>
                        </div>
                        <div class="result-card">
                            <div class="stat-number">37±9 s</div>
                            <p>Ikejime time with electrical stunning</p>
                        </div>
                        <div class="result-card">
                            <div class="stat-number">16±3 min</div>
                            <p>Complete opercular movement loss in ice-slurry</p>
                        </div>
                    </div>
                    
                    <div class="highlight-box">
                        <strong>Critical Finding:</strong> Fish without stunning remained conscious throughout the slaughter process, with confirmed consciousness lasting at least 11 minutes in ice-slurry.
                    </div>
                </div>
            </div>

            <!-- Consciousness Assessment -->
            <div class="canvas-section">
                <div class="section-title">👁️ Consciousness Assessment</div>
                <div class="section-content">
                    <p><strong>Visual Indicators Monitored:</strong></p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Free swimming behavior</li>
                        <li>Equilibrium maintenance</li>
                        <li>Opercular movement patterns</li>
                        <li>Vestibulo-ocular reflex (VOR)</li>
                    </ul>
                    
                    <div class="highlight-box">
                        <strong>Key Limitation:</strong> Visual indicators alone insufficient to confirm unconsciousness. EEG monitoring necessary for definitive assessment when visual cues are absent.
                    </div>
                    
                    <p><strong>Electrical Stunning:</strong> 9/10 fish showed immediate loss of consciousness indicators, but some recovered VOR during ice-slurry processing.</p>
                </div>
            </div>

            <!-- Physiological Responses -->
            <div class="canvas-section">
                <div class="section-title">🫀 Physiological Responses</div>
                <div class="section-content">
                    <p><strong>Heart Rate Patterns:</strong></p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Ice-slurry induced bradycardia due to hypoxia at low temperatures</li>
                        <li>No significant differences between stunning methods</li>
                        <li>Ikejime maintained higher heart rates than ice-slurry</li>
                    </ul>
                    
                    <p><strong>Temperature Changes:</strong></p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Non-stunned fish showed faster internal temperature decline</li>
                        <li>Likely due to increased blood flow and movement from stress</li>
                        <li>Significant temperature drop observed from minute 3 onwards</li>
                    </ul>
                    
                    <p><strong>Stress Hormones:</strong></p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Highest cortisol in non-stunned ice-slurry group</li>
                        <li>Lowest cortisol in anaesthetized groups</li>
                        <li>Electrical stunning didn't reduce cortisol vs. unstunned fish</li>
                    </ul>
                </div>
            </div>

            <!-- Muscle Quality -->
            <div class="canvas-section">
                <div class="section-title">🥩 Muscle Quality Impact</div>
                <div class="section-content">
                    <p><strong>pH Effects:</strong></p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Electrical stunning and ice-slurry led to lower muscle pH</li>
                        <li>Anaesthesia resulted in higher pH and better quality</li>
                        <li>Lower pH indicates stress and strong muscle contractions</li>
                    </ul>
                    
                    <p><strong>Texture Properties:</strong></p>
                    <ul style="margin-left: 20px; margin-top: 10px;">
                        <li>Anaesthetized fish: softer, less chewy, less gummy</li>
                        <li>Better water-holding capacity with anaesthesia</li>
                        <li>Lower pH causes protein denaturation and moisture loss</li>
                    </ul>
                    
                    <div class="highlight-box">
                        <strong>Quality Implication:</strong> PCA analysis showed clear separation between anaesthetized and electrically stunned fish in meat quality parameters.
                    </div>
                </div>
            </div>

            <!-- Experimental Design Issues -->
            <div class="canvas-section">
                <div class="section-title">⚠️ Experimental Design Issues</div>
                <div class="section-content">
                    <details>
                        <summary style="cursor: pointer; font-weight: bold; font-size: 1.1rem; color: #e74c3c; margin-bottom: 15px;">
                            Click to expand: How the study was set up and why it's problematic ⬇️
                        </summary>
                        
                        <div style="background: #fff3cd; padding: 15px; border-radius: 8px; margin-bottom: 15px; border-left: 4px solid #ffc107;">
                            <strong>In Simple Terms:</strong> Imagine trying to test if different medicines work by only giving each medicine to 4-5 people, using different hospitals on different days, and not having a proper way to measure if the medicine actually worked. That's essentially what happened here with fish slaughter methods.
                        </div>
                    
                        <div class="highlight-box">
                            <strong>Critical Sample Size Problem:</strong> Only 32 fish total across 6 treatment combinations (n = 4-5 per group) severely limits statistical power and robustness.
                        </div>
                        
                        <ul class="implications-list">
                            <li><strong>Unbalanced Design:</strong> Unequal group sizes (4-5 fish) impact model assumptions and statistical validity <em>(Like comparing test scores from classes with different numbers of students)</em></li>
                            <li><strong>Tank/Day Confounding:</strong> Only 3 tanks used (one per day) prevents separation of treatment effects from environmental variation <em>(Can't tell if differences are from the treatment or just different tank conditions)</em></li>
                            <li><strong>Pseudoreplication Risk:</strong> Same fish used for multiple measures (visual, physiological, quality) creates non-independent data <em>(Like counting the same person's opinion multiple times in a survey)</em></li>
                            <li><strong>Surgery Timing:</strong> Surgeries staggered by tank/day may introduce unaccounted tank-by-day effects <em>(Operations done on different days might have different conditions affecting results)</em></li>
                            <li><strong>Recovery Period:</strong> 7-day bio-logger recovery may still carry residual surgical stress effects <em>(Fish might still be stressed from surgery, affecting how they respond to treatments)</em></li>
                            <li><strong>No EEG Validation:</strong> Consciousness assessed only via visual indicators not validated for seabream <em>(Like checking if someone is asleep by only looking at them, not using brain monitoring)</em></li>
                            <li><strong>Order Effects:</strong> Treatment randomization limited by tank-day confounding <em>(The order of treatments wasn't truly random due to tank limitations)</em></li>
                        </ul>
                    </details>
                </div>
            </div>

            <!-- Statistical Analysis Weaknesses -->
            <div class="canvas-section">
                <div class="section-title">📊 Statistical Analysis Weaknesses</div>
                <div class="section-content">
                    <details>
                        <summary style="cursor: pointer; font-weight: bold; font-size: 1.1rem; color: #e74c3c; margin-bottom: 15px;">
                            Click to expand: Why the math behind the results is questionable ⬇️
                        </summary>
                        
                        <div style="background: #fff3cd; padding: 15px; border-radius: 8px; margin-bottom: 15px; border-left: 4px solid #ffc107;">
                            <strong>In Simple Terms:</strong> Statistical analysis is like using the right tools to measure things accurately. Here, it's like trying to measure the height of a building with a broken ruler, removing measurements that don't fit your expectations, and not checking if your measuring method actually works.
                        </div>
                    
                        <ul class="implications-list">
                            <li><strong>Underpowered Analysis:</strong> 4-5 fish per group only detects large effects, high risk of Type I/II errors <em>(Too few samples to reliably detect real differences - like trying to determine if a coin is fair by only flipping it 5 times)</em></li>
                            <li><strong>LMM Assumptions:</strong> Linear Mixed Models may violate assumptions with small n and limited replication <em>(Using advanced statistical methods that require more data than available)</em></li>
                            <li><strong>Subjective Outlier Removal:</strong> Two heart rate points removed based on AIC improvement lacks rigorous justification <em>(Removing inconvenient data points to make results look better)</em></li>
                            <li><strong>Inconsistent Statistical Approaches:</strong> Mixed use of parametric/non-parametric tests when assumptions violated <em>(Switching between different statistical methods without clear rules)</em></li>
                            <li><strong>No Visual Indicator Analysis:</strong> All consciousness data presented descriptively without inferential statistics <em>(Just describing what they saw without testing if it's statistically meaningful)</em></li>
                            <li><strong>ANOVA Assumptions:</strong> Small, unbalanced groups undermine normality and homogeneity assumptions <em>(Using statistical tests that don't work well with uneven, small groups)</em></li>
                            <li><strong>Multiple Testing:</strong> No correction across multiple outcomes increases false positive risk <em>(Testing many things at once without adjusting for the increased chance of false findings)</em></li>
                            <li><strong>Missing Effect Sizes:</strong> No Cohen's d or eta squared reported limits biological relevance interpretation <em>(Not telling us how big or important the differences actually are in real-world terms)</em></li>
                        </ul>
                    </details>
                </div>
            </div>

            <!-- Methodological Concerns -->
            <div class="canvas-section">
                <div class="section-title">🔬 Methodological Concerns</div>
                <div class="section-content">
                    <details>
                        <summary style="cursor: pointer; font-weight: bold; font-size: 1.1rem; color: #e74c3c; margin-bottom: 15px;">
                            Click to expand: Problems with how the experiments were actually carried out ⬇️
                        </summary>
                        
                        <div style="background: #fff3cd; padding: 15px; border-radius: 8px; margin-bottom: 15px; border-left: 4px solid #ffc107;">
                            <strong>In Simple Terms:</strong> These are like procedural errors in a cooking recipe - using different ovens at different temperatures, having some cooks who are better than others, and not measuring all the ingredients you claim are important. Even if the recipe idea is good, these errors make the results unreliable.
                        </div>
                    
                        <div class="highlight-box">
                            <strong>Operator Bias:</strong> Manual ikejime application showed variable success (2/4 failed in non-stunned fish), introducing procedural inconsistency.
                        </div>
                        
                        <ul class="implications-list">
                            <li><strong>Environmental Differences:</strong> Stunner water (8‰ salinity, different temperature) vs. tank conditions may influence stress response <em>(Like testing medicine effects while changing the patient's environment)</em></li>
                            <li><strong>Incomplete Factorial Design:</strong> Not all stunning-slaughter combinations fully crossed limits independent effect assessment <em>(Not testing all possible combinations makes it hard to know which part of the treatment caused the effect)</em></li>
                            <li><strong>Missing Key Metrics:</strong> No haematocrit/haemolysis despite K⁺ implications; chloride not measured despite osmolality discussion <em>(Claiming to study blood health but not measuring important blood components)</em></li>
                            <li><strong>Assay Limitations:</strong> Detection limits and variances of commercial kits not reported or validated <em>(Using measurement tools without knowing how accurate they are)</em></li>
                            <li><strong>Observer Bias Risk:</strong> No mention of blinding for behavioral or physiological assessments <em>(Researchers knew which treatment each fish got, potentially influencing their observations)</em></li>
                            <li><strong>PCA Justification:</strong> Multivariate analysis unclear with small sample size for dimensionality reduction <em>(Using complex statistical analysis methods that need more data than available)</em></li>
                            <li><strong>Crowding Duration:</strong> Excluded variable may still contribute to unexplained variance <em>(Ignoring a factor that might actually matter to the results)</em></li>
                        </ul>
                    </details>
                </div>
            </div>

            <!-- Conclusions -->
            <div class="canvas-section">
                <div class="section-title">💡 Main Conclusions</div>
                <div class="section-content">
                    <div class="highlight-box">
                        <strong>Primary Finding:</strong> Slaughter without stunning causes significant welfare concerns and produces inferior meat quality.
                    </div>
                    
                    <p><strong>Method Rankings (Welfare + Quality):</strong></p>
                    <ol style="margin-left: 20px; margin-top: 10px;">
                        <li><strong>Anaesthesia + Ikejime:</strong> Best welfare and quality (not commercially viable)</li>
                        <li><strong>Ikejime alone:</strong> Good welfare, excellent quality (labor-intensive)</li>
                        <li><strong>Electrical stunning + Ikejime:</strong> Uncertain welfare, good quality</li>
                        <li><strong>Electrical stunning + Ice-slurry:</strong> Uncertain welfare, poor quality</li>
                        <li><strong>No stunning + Ice-slurry:</strong> Poor welfare, poor quality</li>
                    </ol>
                    
                    <p style="margin-top: 15px;"><strong>Critical Need:</strong> Development of validated, scalable stunning methods that ensure immediate and sustained unconsciousness while maintaining product quality for commercial aquaculture operations.</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
