# Absurd Finance: The credit card web3 needs

## Introduction

In recent times, newer generations have faced increasing hurdles in accessing credit and a resulting widespread lack of credit history. 

Traditional financial institutions, wary of high interest rates imposed by central banks and geopolitical instability, have become reluctant to extend credit, thereby exacerbating the issue. Moreover, as of now there is no web3 native loan originator, posing further challenges for these individuals by demanding higher assurances or completely refusing them as customers. 

Absurd Finance, through an innovative approach, seeks to address these challenges. By integrating open banking and on-chain data, it accurately assesses borrowing power and provides uncollateralised revolving credit lines to vetted borrowers linked to a credit card. In this way, Absurd Finance presents the first credit card with a complete fully on-chain backend.

## The Unfolding Credit Crisis

The financial landscape has evolved dramatically, with the purchasing power of younger generations, including GenZ, experiencing a marked decline in recent times. Low wages, job instability, and fragmented earnings have led to a lack of credit availability for many individuals. What were once simple expenses, such as purchasing a high-quality garment, have transformed into an elusive luxury for a significant portion of the population.

GenZ, in comparison to the baby boomer generation, grapples with more significant obstacles when it comes to credit access. This economic disparity has resulted in a substantial decline in their purchasing power, impeding their ability to participate in various experiences and fulfil aspirations that were once taken for granted. Consequently, a growing divide is emerging between those who are financially privileged and those struggling to secure credit for their needs.

Millennials, reacting to this shifting financial environment, have shown a preference for spreading sizeable expenses over several months, as opposed to making immediate payments. This change in spending habits has triggered a surge in *Buy Now Pay Later* (BNPL) services, such as Klarna or Scalapay, and a growing reliance on credit cards to manage expenses. Even in the EU market, traditionally hostile to credit, there's a gradual acceptance of BNPL and credit cards as convenient and accessible means of financing.

Despite its rapid growth and innovation, the crypto industry is not exempt from unique hurdles in the realm of credit access. Traditional credit institutions often lack attention in their assessment of cryptocurrencies and DLT financial use cases as a from of gambling and tend to overlook on-chain assets or salaries when evaluating potential borrowers, to the extent of treating these factors as red flags. This bias has thwarted the potential integration of crypto assets as a viable path in the lending process.

## Uncollateralised Lending in Web3

In the existing DeFi landscape, the predominant form of lending is overcollateralised. This means that borrowers are required to secure their loans by putting up more in assets than they're borrowing. While this approach mitigates risk for lenders, it presents a considerable barrier for a majority of potential borrowers who may not have sufficient collateral to offer.

Uncollateralised lending, on the other hand, removes the need for borrowers to secure loans with collateral, thereby allowing a broader range of individuals and businesses to access needed funds. This approach becomes increasingly important in web3, where a large part of the user base may primarily hold or earn their wealth in crypto assets, which are not conventionally considered by traditional banks as viable collateral.

The advent of uncollateralised lending in web3 opens up new opportunities for these individuals to access credit, encouraging economic activity and fostering growth in the digital economy. By assessing creditworthiness using a combination of traditional financial data and on-chain metrics, protocols like Absurd Finance aim to make uncollateralised lending a reality in web3, promoting financial inclusivity and the democratisation of finance.

## Lending as a Driver of Economic Growth

> "Perhaps the largest financial value built directly upon reputation lies within credit and uncollateralised lending." — Vitalik Buterin

Lending, in both traditional and digital economies, plays a crucial role in stimulating economic growth. It serves as a catalyst for a variety of economic activities, from consumer spending and business investment to entrepreneurial initiatives and innovation.

In essence, lending facilitates the flow of money from those who have a surplus (savers or investors) to those who need extra funds (borrowers). This flow of funds is essential for both business development and consumer spending. Businesses, whether small start-ups or large corporations, often rely on loans to finance expansions, acquire necessary equipment, or invest in research and development. Similarly, consumers use credit for a variety of purposes, including purchasing homes, cars, and other goods, or funding education.

When businesses can invest in growth and consumers can spend more, it leads to an increase in production, job creation, and overall economic activity. Additionally, the interest paid on these loans provides a return for savers and investors, further encouraging saving and investment.

In a nutshell, lending, and particularly uncollateralised lending, is a critical component in fuelling economic growth. As digital economies continue to grow and evolve, protocols like Absurd Finance are setting the stage for this transformative economic activity to expand into web3. By embracing uncollateralised lending, they not only drive economic growth in the digital world, but also ensure that this growth is inclusive and accessible to all.

## Introducing Absurd Finance

Absurd Finance emerges as an innovative solution to the credit hurdles encountered by the web3 generation. It caters to individuals who primarily earn or hold their wealth in on-chain assets, thus granting them access to credit benefits that were previously out of reach.

To accurately assess borrowers' creditworthiness, Absurd Finance integrates the capabilities of open banking with on-chain data. This inclusive approach allows Absurd to formulate a more holistic and accurate credit score, ensuring credit is extended to previously overlooked customers based on their actual financial situation.

Beyond facilitating borrowing, Absurd Finance also nurtures peer-to-peer lending opportunities. Through smart contracts, Absurd empowers vetted borrowers to secure uncollateralised credit lines from lenders within the network. This peer-to-peer lending model benefits both borrowers and lenders, allowing individuals seeking an extra yield to actively participate in the lending process.

## How It Works

The protocol strives to achieve maximum decentralisation and fully takes advantage of DeFi legos to build a seamless user experience.

### Lending
An ERC4626 token Vault collects lenders' deposits issuing share tokens and gets instructed by the *Manager* to lend to new and existing credit lines. Once a borrower repays their due amount, the profits are distributed to the lenders over a few days to prevent value capture attacks.

### Borrowing
When a borrower is accepted, a credit account (represented as an *ERC4337* Smart Contract Account) is deployed and linked to the issued physical and virtual card. That means funds can only be spent via the card and there is limited control from the governance, that can only close the credit account and return funds to the Vault.

As the loan is uncollateralised, there exists a possibility that the borrower may default on their repayments. To mitigate this risk, Absurd Finance utilises a Risk Model to analyse open banking and on-chain data. This model aids in providing an accurate credit score, thus determining the borrower's credit limit.

### Credit Score
Credit scoring leverages an internal model combined with industry-leader Algoan Open Banking score to obtain a full-round representation of the financial situation of an individual. Data is passed to Absurd own Chainlink oracle that gives back the maximum credit line value in EUR (or 0, in case of a rejection), thus preserving the user privacy.

Using Absurd Finance credit, borrowers build a unique on-chain credit footprint which over time will grant rights to more sophisticated borrowing products.

### Enforcement
As the loan is uncollateralised, there could be a chance the borrower does not repay what is due.
If such situation arises, a Kleros decentralised court is spun off and, in case of a positive decision, the case is passed to the local debit collection agency via Debitura. Subsequently, the borrower is reported to the local credit bureau as bad payer, hintering their credit score for the years to come.

An interesting aspect of enforcement is the *social credit*, the reputation risk linked to a possible default. As the web3 ecosystem is moving towards an enclosed community, purposely failing to repay the loan could hinter or even sever relationships of the borrower with the rest of the ecosystem.

## Capital Sourcing
Apart from attracting liquidity from individual investors/LPs, Absurd can also source funds for credit lines through the issuance of zero-coupon bonds and collateralised loan obligations (CLOs). 

Zero-coupon bonds are debt securities that do not make periodic interest payments. Instead, they are issued at a discount to their face value, and upon maturity, the bondholder receives the face value of the bond. The discount rate implicitly defines the bond's yield. The present value (PV) of a zero-coupon bond can be calculated using the formula:

$$
PV = F / (1 + r)^n
$$

where $F$ is the face value of the bond, $r$ is the yield or discount rate, and $n$ is the number of periods until maturity. Issuing these bonds provides an upfront influx of liquidity to the Vault, to be repaid fully at the bond's maturity.

Collateralised loan obligations (CLOs) are another tool for sourcing liquidity. A CLO is a type of structured credit product backed by a pool of loans. The Vault can bundle together a variety of credit lines and sell them as a CLO to investors. These CLOs are divided into tranches based on risk level and return. Investors who purchase riskier tranches receive higher interest rates, compensating them for the added risk. 

The pricing of CLO tranches typically involves complex financial modeling. However, a simple approximation might involve the use of weighted average cost of capital (WACC) for the pool of loans, factoring in the likelihood of default for each loan and the recovery rate in the event of default. Cash flows are then discounted at this WACC to determine the present value of the tranche. For a tranche with expected cash flows $CF_t$ at each period $t$ and a WACC of $r$, its price $P$ can be estimated as:

$$
P = \sum_{t=1}^{n} \frac{CF_t}{(1 + r)^t}
$$

Such financial instruments provide a powerful mechanism to raise significant amounts of liquidity while spreading the risk among various investors.

## Extras
As for all the credit cards, Absurd ones comes with a wide range of handpicked perks and rewards, from cashbacks to bonus points (ERC20 tokens) redeemable for prizes.
All cards come with travel and medical insurance, fraud protection and are available everywhere Visa is accepted.

## Regulatory Compliance
To protect user privacy and streamline the onboarding process, Know Your Customer (KYC) and Anti-Money Laundering (AML) procedures utilise reusable zero-knowledge credentials. The credentials can be produced by trusted entities, e.g., traditional banks, and accepted by Absurd Finance. This ensures regulatory compliance while reducing friction during user onboarding.

## Technical Specifications

### Credit Scoring Oracle

Underwriting retail borrowers is an intricate process aimed at assessing the creditworthiness of potential borrowers whilst safeguarding the lender's interests. Absurd Finance harnesses a comprehensive evaluation model that synergises traditional financial metrics and on-chain data.

The process commences with the collection of key borrower information, which incorporates both traditional credit history and on-chain activity. These two distinct data streams are then independently processed through the Algoan Open Banking model and Absurd Finance's proprietary internal model, respectively.

Let's denote the output of the Algoan model as $A$ and the output of the internal model as $I$. Each of these outputs represents a creditworthiness score based on the respective datasets.

The final creditworthiness score $S$ is formulated using a weighted sum of $A$ and $I$. It is represented mathematically as:

$$S = w_1 \cdot A + w_2 \cdot I$$

where $w_1$ and $w_2$ are the weights applied to the Algoan score and the internal score, respectively. The values of $w_1$ and $w_2$ are optimised to best represent the borrower's financial standing.

The score $S$ is then used to determine the maximum credit line value $C$ that a borrower is eligible for, given by:

$$C = f(S)$$

where $f$ is a function that translates the score $S$ into a credit line value in EUR. If $S$ falls below a predetermined threshold, $C$ would be 0, indicating a rejection.

This mathematical model of underwriting allows Absurd Finance to extend credit to a broad range of borrowers in the web3 environment with precision, thereby promoting financial inclusivity.

### Vault

The *Vault* is a yield-bearing token that uses to the ERC4626 standard. Its primary role involves sourcing liquidity from Liquidity Providers (LPs) and secondary market (Bonds, CLOs), subsequently lending this liquidity to borrowers.

#### Accounting

The Vault maintains four state variables for accounting: 

* netLoans
* currentProfits
* currentLosses
* latestRepay

The variable `netLoans` keeps track of the total loaned amounts. Simultaneously, `currentProfits` and `currentLosses` record the total *locked* profits and losses respectively at the time of the latest repayment. The timestamp of the latest repayment is stored in `latestRepay`.

#### Locking

Accrued fees and losses undergo a locking period to moderate fluctuations in the Vault's token price per share and protect the Vault from value capture attacks. The formula for the same is as follows:

$$
L = P\cdot\frac{(T_L+T_U-T)_+}{T_U}
$$

Here, $L$ is the function's result, $P$ represents `currentProfits`, $T_U$ is the Vault's `unlockTime` (a constructor value), $T_L$ is `latestRepay`, and $T$ is the current block's timestamp. The subscript "$+$" signifies the positive part.

Specifically, when $T = T_L$, i.e., at the time of profit (or loss) generation, we have $L = P$ and all `currentProfits` are locked. After the locking period, i.e., $T \ge T_L + T_U$, we have $L=0$, which means all fees are unlocked. For $T_L \le T \le T_L + T_U$, we have 

$$
L = P\cdot\left(1- \frac{T - T_L}{T_U} \right)
$$ 

This indicates that the fees and losses unlock *linearly* over time.

#### Total Assets

Borrowing from and repaying to the Vault alters the value of `totalAssets`, as defined in the original ERC4626 contract, and subsequently the resulting token price per share. Considering that loans are temporarily moved from the vault and fees must undergo a locking period, we need to incorporate these factors into the definition of total assets. Thus, we have:

$$
totalAssets = super.totalAssets + netLoans + calculateLockedLosses() - calculateLockedProfits()
$$ 

Mathematical overflow and capping checks ensure that `totalAssets` remains $> 0$ and the computation above never overflows, adhering to the ERC4626 standard for overriding this function.

#### Free Liquidity

Free Liquidity refers to the amount of liquidity that can be freely borrowed or withdrawn. It is crucial to note that it would be impossible to transfer an amount exceeding the Vault's native token balance. Furthermore, locked profits should not be available for borrowing or withdrawal. Therefore, with $L = calculateLockedProfits()$, we define:

$$
freeLiquidity = 
\begin{cases}
native.balanceOf(vault) - L &\text{ if } L > 0 \\
native.balanceOf(vault) &\text{ otherwise}.
\end{cases}
$$

Note that locked losses are not included in this calculation, as this would permit the borrowing of lost assets, thus compromising the Vault's mathematical integrity.

One significant caveat is that *the entirety of the free liquidity cannot be borrowed or withdrawn at once*. Indeed, this could cause the Vault to become *unhealthy* as per the ERC4626 standard. Therefore, the functions that move funds include a check to revert if all free liquidity is taken. 

## Borrow

The Vault's `borrow` function, which can only be accessed by the owner, directly transfers the `amount` of the native asset from the Vault to a `receiver`. To account for the loan, the `netLoans` state variable is incremented by the `amount`.

To ensure the Vault remains *healthy* as per the ERC4626 standard (i.e., the Vault's balance cannot be zero if the Vault's supply is more than zero), the `amount` must be *strictly less* than the Vault's *free liquidity*.

Checking the formulas for `totalAssets()`, we observe that the `borrow` function does not immediately alter the total assets after being called: the total assets are an *invariant* of the borrow function.

#### Repay

The Vault's `repay` function, accessible only by credit lines, directly transfers `assets` of the native asset from the `repayer` to the Vault. The `debt` is the loan amount that this function is designated to repay: the `netLoans` state variable is reduced by `debt` within this function.

The parameter `assets` can either be larger or smaller than `debt`. If it's larger, we denote the difference `assets - debt` as the *fees* paid to the Vault for lending its liquidity; if it's smaller, we consider the difference `debt - assets` as the *loss* the Vault incurs for lending its liquidity. We call the former scenario a *Good Repay Event (GRE)* and the latter a *Bad Repay Event (BRE)*. 

Both the fees and the losses undergo a *locking period* which safeguards the Vault from attackers draining all incoming fees and disincentivises LPs from frontrunning losses. To implement this, the `currentProfits` and `latestRepay` variables are updated as 

$$
currentProfits \mapsto calculateLockedProfits() + (assets - debt)_+
$$ 

$$
currentLosses \mapsto calculateLockedLosses() + (debt - assets)_+
$$

$$
latestRepay \mapsto T
$$

where $T$ is the current block's timestamp, and the subscript "$+$" denotes the positive part. 

In the GRE scenario, the `currentProfits` variable increases, whereas, in the BRE scenario, the `currentLosses` variable increases. After each repayment, the `latestRepay` is updated to the current timestamp.

One primary advantage of the locking period is that the locked profits and losses linearly decay over time, ensuring the Vault's token price per share doesn't sharply decrease or increase, and thus providing a fair price for all LPs and token holders.

The `repay` function immediately alters the total assets after being called: it increases the total assets by the amount of `assets` (fees included), and reduces the total assets by the amount of `debt` that is repaid.

### Portfolio Management
In order to optimise the utility of undrawn funds within the credit lines, a portion of these funds will be invested in tokenised Treasury bills obtained via *Backed Finance*. This strategy provides a base APY on the assets, ensuring that even if borrowers do not utilise their entire credit lines, the invested funds continue to generate returns. This form of portfolio management not only safeguards liquidity but also adds an additional layer of financial efficiency, thereby improving the overall value proposition for investors of the protocol.

In terms of estimation, it would look like the following:

Let:
- $C$ be the total amount of undrawn credit lines,
- $R$ be the percentage of undrawn funds that are invested (expressed as a decimal), 
- $I$ be the annual interest rate of the investment (expressed as a decimal), 
- $A$ is the amount invested,
- $Y$ is the yield earned per year.

We can express the amount to be invested, $A$, as a function of the total credit lines and the chosen allocation rate:

$$A = R \times C$$

The annual yield $Y$, can be calculated using the simple interest formula:

$$Y = A \times I$$

This provides a simple formula to calculate the additional annual yield that can be earned by investing a percentage of the undrawn credit lines. Please note that this is a simplified model and does not account for factors such as compounding interest, risk, investment diversification, and changes in interest rates over time.

### Credit Lines
A credit line is an ERC4337-compliant smart contract acting as a specialised account, which allows just the specific borrower and the card processor to withdraw funds. Doing so, the credit line contract becomes an abstracted user account that can be crafted to include unique logic, rules and limitations. For instance, it may stipulate that not just the borrower can withdraw funds but also other delegates, or that the credit line can be paid back just over a period of time, rather than all at once. 

This opens up a myriad of possibilities, allowing for a more robust and flexible implementation of credit lines in DeFi. This abstraction also greatly simplifies the user experience by letting users interact directly with their smart contract wallets instead of having to manage multiple EOAs.

## Conclusions
Absurd Finance, as a pioneering solution, aims to bridge the credit access gap for the web3 generation. By leveraging the strengths of traditional financial systems and DeFi, Absurd Finance breaks new ground, enabling more individuals to participate in the economic growth of web3. As a result, Absurd Finance is paving the way for a more inclusive and financially empowered future in the digital economy.
