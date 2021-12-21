---
permalink: /Projects/
---

Here are the course projects I have undertaken during my PhD studies.

# 1. A Review of EM Algorithm for Missing Data
- Course: Missing Data
- Date: 2020/04 - 2020/05

Expectation-Maximization algorithm (EM) is a numerical approximation method used primarily to iteratively find the maximum likelihood estimation (MLE) of the parameter (Dempster et al., 1977). The iteration of EM begins with the execution of the Expectation step (E-step), followed by the Maximization step (M-step). The iteration continues until convergence is attained. The original idea of the EM Algorithm is motivated by the missing data problem under the Missing at Random (MAR) assumption. The EM algorithm can estimate parameters, and the E-step finds the integral of the expected full data likelihood conditional on observed data. Naturally, the integral of the E-step cannot be carried out analytically; therefore, it is necessary to employ simulation strategies to find the parameter estimation. The Markov Chain Monte Carlo method (MCMC) is helpful to find the target distribution of the parameter. Two MCMC methods are commonly used to resolve this issue: Monte Carlo EM (MCEM) and Stochastic Approximation of EM (SAEM). In this report, we briefly review the concepts and the related algorithms of EM, including MCEM (Wei & Tanner, 1990) and SAEM (Delyon et al., 1999).  

*Keywords*: expectation-maximization algorithm, markov chain expectation-maximization, stochastic approximation of expectation-maximization

[Download report here](https://psyen0824.github.io/website/files/A_Review_of_EM_algorithm_for_Missing_Data.pdf)


&nbsp;
&nbsp;

---
# 2. Developed R Package "MixPoiRayExp": An Expectation-Maximization Algorithm for Finite Mixture Models
- Course: Computational Statistics
- Date: 2020/10 - 2020/12

Finite mixture models are frequently seen in real-world data applications. To overcome the difficulties of density estimation, it is necessary to isolate the true cluster of the data. The EM algorithm is commonly used to obtain the parameter estimates of the mixture model.  Most of the published R packages, such as mixture, mclust, and EMCluster, were developed primarily for handling mixture Gaussian cases.  For cases outside the scope of mixture Gaussian, the relevant R packages are quite limited.  To cope with this problem, we develop a new R package MixPoiRayExpin. MixPoiRayExp can provide the point estimation results with its precision in the following finite mixture models: mixture Poisson, mixture exponential, and mixture Rayleigh. Two additional functions were developed in MixPoiRayExp to help users obtain reliable results. These functions provide suggestions of the number of mixture components and initialization strategies for the EM algorithm.


*Keywords*: finite mixture model, expectation-maximization algorithm, mixture Poisson, mixture Exponential, mixture Rayleigh 

[Download report here](https://psyen0824.github.io/website/files/Developed_R_package_entitled_MixPoiRayExp_An_Expectation_Maximization_Algorithm_for_Finite_Mixture_Models.pdf)


&nbsp;
&nbsp;

---
# 3. Using Machine Learning Classification Methods and SMOTE Resampling Skills to Predict Suicide Risk of Hotlines Callers
- Course: Health Analytics
- Date: 2019/03 - 2019/12
  
Suicide hotlines are an essential prevention tool in reaching people with suicidal ideation. The Taiwanese government established the National Suicide Prevention Hotlines (TNSPH) in 2009 to reduce the country’s suicide rate. Each year, TNSPH receives around 70,000 phone calls. The primary responsibility of the volunteers is evaluating the suicide risk of the callers, but volunteers struggle to assess 60% of callers due to limited background information and call time duration. This research uses 8 machine learning classification methods to predict suicide risk for this unassessed group of callers using the characteristics of known suicide risk groups. Since the TNSPH data is exceptionally imbalanced, the prediction may dangerously bias results toward the majority group (no suicide risk or low suicide risk). To overcome this issue, several sampling methods were used to balance the data and improve model predictive accuracy. These methods include the Simple Random Sampling and Synthetic Minority Over-Sampling Technique (SMOTE). The Random Forest Multinomial Model via SMOTE techniques was selected as the best model because of its significant improvement on the false negative rate of suicide risk groups and avoidance of overfitting. This process effectively identifies individuals at high risk of suicide, which allows TNSPH volunteers to prioritize contacting them and saves countless lives.

*Keywords*: suicide hotline, suicide risk, imbalanced data, synthetic sample  

[Download report here](https://psyen0824.github.io/website/files/Using_Machine_Learning_Classification_Methods_and_SMOKE_Resampling_Skills_to_Predict_Disease_Risk.pdf)
  

&nbsp;
&nbsp;

------ 
# 4. Using Bayesian Ordinal Regression Model to Identify Suicide Risk Factors
- Course: Bayesian Statistics
- Date: 2020/03 - 2020/05

Suicide hotline is a vital prevention tool in reaching people with suicide ideation. The Taiwanese government established National Suicide Prevention Hotlines (TNSPH) in 2009 to reduce the country’s suicide rate. Each year, TNSPH received around 70,000 phone calls. Volunteers must evaluate the suicide risk of the callers, but about 60% of callers cannot be assessed due to limited background information and call time duration. To efficiently identify the suicide risk during the phone call, exploring the essential predictors is the objective of this research. We use Bayesian Ordinal Regression Model to identify the critical predictors of known suicide risk groups. TNSPH volunteers may employ these crucial predictors to improve their consulting skills while interacting with the callers, saving countless lives. 

*Keywords*: suicide risk, bayesian ordinal regression Model, MCMC  

[Download report here](https://psyen0824.github.io/website/files/Using_Bayesian_Ordinal_Regression_Model_to_Identify_Suicide_Risk_Factors.pdf)
  

&nbsp;
&nbsp;

---

# 5. Proportional Odds Models and Partial Proportional Odds Models for Ordinal Data Analysis
- Course: Generalized Linear Model
- Date: 2019/04 - 2019/05
 
Care must be taken when dealing with ordinal data because ordinal data have both qualitative and quantitative characteristics. Some researchers model ordinal data by assigning scores to categorical outcomes and performing regression; however, ordinal regression may misclassify the outcome variable to the adjacent category. Other researchers utilize the qualitative characteristic of the ordinal data and apply the generalized logit model. Although, this model may produce unnecessary parameter estimations, which makes the model too complicated for use. McCullagh (1980) proposes using the proportional odds model to solve these methodological issues. Currently, using the proportional odds model is the most common technique for analyzing ordinal data because the model is simple and easy to interpret.

*Keywords*: ordinal outcome, proportional odds model, ordinal regression, generalized logit model

[Download report here](https://psyen0824.github.io/website/files/Proportional_Odds_Models_and_Partial_Proportional_Odds_Models_for_Ordinal_Data_Analysis.pdf)


&nbsp;
&nbsp;

---

# 6. Estimation for the Unknown True Concentration of Environmental Analytical Data
- Course: Linear Model
- Date: 2018/10 - 2018/12

We use the statistical model to describe the environmental analytical measurements. To reduce the bias naturally occurring in the observation process, the measurements come from the interlaboratory data which is divided into three different levels of concentration respectively having five replications. The statistical model is constructed using the nonlinear format instead of the traditional linear format, for accounting for the larger variation of the analyte in a higher concentration level. We estimate the model parameters following the work of Bhaumik and Gibbons (2005), which adopts the method of moments that is fast in execution. After obtaining the model parameters, we further apply this model to estimate the unknown true concentration and verify the variation property of the analytic observations.

*Keywords*: linear mixed model

[Download report here](https://psyen0824.github.io/website/files/Estimation_for_the_unknown_true_concentration_of_environmental_analytical_data.pdf)


&nbsp;
&nbsp;

---


# 7. Two-Component Mix Model and Gamma Mixed Model for Estimating the Unknown True Concentration of Ground Water 
- Course: Independent Study 
- Date: 2019/01 - 2019/08

Traditional environmental analysis commonly accepts original measurements as true concentration without considering uncertainty, which may be unrealistic. To address this uncertainty, statistical models can help evaluate environmental analytical measurements. One specific approach considers data characteristics, like heteroscedastic measurement errors and between-laboratories variability, to reach a more accurate estimation of the true concentration of analytical measurements. Kim and Bhaumik (2018) extended the nonlinear two-component mixed model proposed by  Bhaumik and Gibbons (2005) and performed the predictive model to estimate the true concentration of groundwater data. This model obtains the parameter using the iteratively reweighted maximum marginal likelihood (IWMML) proposed by Gibbons and Bhaumik (2001). A multiplicative gamma mixed model serves as a possible alternative to this two-component model, and the parameter of the gamma model can be estimated by the adaptive Gauss-Hermite quadrature (AGQ) method. The lab-specific random effects are further estimated by the Empirical Bayes method. We conducted a statistical simulation study to evaluate and compare the model performance in Kim and Bhaumik’s two-component model and the gamma mixed model. Due to the complexity of the likelihood function of the gamma model, the current R packages—including lme4, GLMMadaptive, R2admb, glmmADMB, and the Zelig—all failed to obtain the parameter estimation. As a result, we performed the work of estimation in SAS using proc NLMIXED. After obtaining the point estimation and interval estimation of the model parameters, we further applied this model to predict the unknown true concentration and verify the variation property of the analytic observations.

*Keywords*: two-component mixed model, gamma mixed model,  uncertainty, groundwater

[Download report here](https://psyen0824.github.io/website/files/Two-Component_Mix_Model_and_Gamma_Mixed_Model_for_Estimating_the_Unknown_True_Concentration_of_Ground_Water.pdf)


&nbsp;
&nbsp;

---

# 8. Using False Discovery Rate Procedure to Detect Disrupted Connectivities in Late-Life Depression
- Course: Linear Model
- Date: 2018/10 - 2018/12

The prevalence rate of patients with Late-life depression (LLD) is estimated to be 4.7% in the U.S. LLD is a leading cause of disability in older adults, and it causes a severe burden of disease. People who suffer from LLD are due to neurological disruptions. Therefore,  identifying the disrupted brain networks and thus locating neuroimaging biomarkers could better understand how to treat patients with LLD. Functional magnetic resonance imaging (fMRI) is essential for measuring functional brain connectivity. Bhaumik et al. (2018) developed a mixed-effects model to detect disrupted neuroconnectivities considering within-subject correlations and between-group variability. They also resolved the issue of multiple comparisons by controlling for False Discovery Rate (FDR). In this report, our purpose is to reproduce Bhaumik’s study and examine the performance of the FDR method. We propose a mixed-effects model to identify those links whose correlations are significantly changed in depressed subjects compared with healthy subjects and use Bhaumik et al.' s/the authors' real-world data set for LLD. We significantly detected up to 793 links (21.2%) among 3,741 brain links using the traditional p-value performance (e.g., alpha = 0.05). This study implements the FDR approach to address spurious detection from the p-value method. FDR requires a q-value cutoff representing the minimum FDR at which the test can be called significant. There is no such gold standard level for FDR, and it may vary from study to study (generally 0.05 - 0.20). The choice of q-value is challenging, so this study reveals the number of significant links under the different q-value cutoffs. Through controlling the q-value level of 0.09, we successfully identified 183 disrupted links for future therapeutic benefit.

*Keywords*: false discovery rate, q-value, functional magnetic resonance imaging, late-life depression

[Download report here](https://psyen0824.github.io/website/files/Two-Component_Mix_Model_and_Gamma_Mixed_Model_for_Estimating_the_Unknown_True_Concentration_of_Ground_Water.pdf)


&nbsp;
&nbsp;

---




