# Doc Folder

Your project report goes here. It is mandatory to use one of the templates (latex or word) that you find herein.

Save the final report as report.pdf

 




Lecture with Computer Exercises:
Modelling and Simulating Social Systems with MATLAB

Project Report


The empires are back: Who will win the currency wars?


Guillermo Fernando Valencia A





Zürich
May 25  2012 
  
Agreement for free-download

We hereby agree to make our source code of this project freely available for download from the web pages of the SOMS chair. Furthermore, we assure that all source code is written by ourselves and is not violating any copyright restrictions.




Guillermo F Valencia Arana  




 
Table of content


1.)	Abstract

2.)	Individual Contribution


3.)	Introduction and Motivation


4.)	Description of the model 


5.)	Implementation and code


6.)	Simulations, results and discussion


7.)	Summary and Outlook


8.)	References



 
Abstract

We model currency wars based on evolutionary game theory. We find that when countries apply tit-for tat strategies economical blocks emerges.  Based on the framework created by (Helbing, 2011) we model currency wars as a confrontation between two block with antagonical currency systems. We find   the key variables to understand where a new standard emerges and who will win the currency war or if the two currency standards could coexist.  Finally, we model the distribution of firm size inside every block. We found that the size distribution follow a power laws. The distribution is less skewed where the is coordination between blocks and highly skewed is when there is  prisoner’s dilemma or a coexistence scenario.

Individual contributions

The contribution of this project is the application of different frameworks of evolutionary game theory to evaluate the possible outcomes of a currency war. The aim of this project is to understand the most important underlying mechanisms of trade among economical blocks with antagonic interests.

In the first part of this report we want to develop a thinking framework that provides some insight to policy makers and other stakeholders of the currency wars. Policy makers could use our approach from the point of view of incentives design. While institutional investors and pension funds could use it as a multi-scenario “map” with only a few intuitive parameters easy to translate into macro-economical currency strategy. The focus of this multi-scenario “map” is to enable long-term investors to have a better risk management inside the  “trade battle”.

We present two different models. The first one is the standard iterated prisoner dilemma (IPD). The second is a multigame model. The IPD, shows when countries use “Tit for Tat” strategies will create trading blocks, where emerging markets (CURRENCY CONTROLLERS) grow more than developed markets. (PRINTERS). 

The iterated prisoner dilemma is a first approach with many unrealistic assumptions. For example, that every couple of countries is facing a prisoner dilemma. Why to be restricted to a prisoner dilemma payoff schema? It also assumes that every pair of countries has the same military or political power and that is of course un-realisitc.  Finally, it does not give any insight in terms of policies design, how to connect the model with the empirical data or how to define an investment strategy.

The second model begins where the first one ends. Therefore it assumes the existence of economical blocks with antagonic interests. This model is based on the paper Cooperation, Norms and Revolution by Helbing and Johansson. (Helbing, 2011) We assume the existence of two sets of countries with two opposite interests. As we mention before we are interested in modelling developed markets and emerging markets trade. In particular, today what developed markets consider like a free trade policy is not for emerging markets and vice versa.  The cooperative population inside every block grows according to the standard equation of dynamical replicators. (Cressman, 1995)

In this model countries could interact inside the same block or with countries of other blocks.  We assume symmetrical 2X2 matrix allowing countries to face 4 different games: Prisoner Dilemma, Harmonic game, Hawk –Dove game, and Stag Hunt game. Three control parameters are introduced: Coordination, Trust and Power. Coordination and trust determine the games payoff matrix and power captures the GDP differences or military power differences. (Weibull, 1995)

We also propose empirical proxies for these parameters: 

•	COORDINATION: short term interest rates discounting inflation. 
•	TRUST: Credit growth differential between the two blocks. 
•	POWER: GDP or  

This model shows the existence of four possibilities; all countries cooperate and accept the other block  “trade norm” (Harmony Game), two trade norms could coexist (Haw and Dove Game), Bi-stability between the “trade norm” (Stag-Hunt Game) and finally a currency war where nobody cooperates and there is no “trade norm”.

In the final part of the model we make the extension from blocks of countries to a blocks of companies. In this section we are interested in studying the firm’s size probability distribution.  We assume that firms in has 2 sources of growth; one is to create economies of scale or scope, and the other is the integration with supplier an customers allowing lean process generating value be means of lean processes or being more innovative.


The combination of this process shows many interesting results it is consistent with the stylized fact of the collective dynamic of firms where the size distribution is skewed.

We show that when currency blocks are facing a currency wars the company size is only determined by the ability of the company to create economies of scale and scope and in this scenario the size distribution follows a Gibrat dynamics (Sornette, 2008). One of the critics to the Gibrart model is that assume that the companies growth rate is Gaussian and   uncorrelated so there is not connection with the business cycle. 

Our contribution in this model is that we make explicit the connection between firm’s size distribution and the business cycle.

According to the ETH regulation I would like to mention that this project is also part of project in the class of Didier Sornette in the chair of enterpenurial risks in a framework for risk detection called Risikopedia .  This project is also is part of my master thesis.





Introduction and Motivations
Since the beginning of the capitalism international trade has been questioned.  Exponents of the Laissez –Faire defend that free trade increases the world surplus thanks to increase in global specialization.












Nevertheless, no country became a global power leader without an industrial policy that includes some strategic protectionism measures. Historically, currency wars appear when there is a technological change that modified the predominant socio-economical world order (Table 1).  











 


Figure  1  Developed market with monetary 
supply stimulus  with a flexible exchange rate.




In this project we would like to present currencies beyond the concept of currencies as a medium of exchange, liquidity or value storage. Currencies reflect   paradigms. They are associated with the dominant and the challenging cultures of the moment. Therefore, currency wars reflect a conflict between technological and socio-economical paradigms.

The mainstream model to understand the relationship between exchange rate and   GDP is the Mundell-Fleming model.  This model part from what Steven Keen  will describe as the totem of macroeconomics; the simultaneous equilibrium between supply and demand in the money and goods market. This model describes two regimens; the flexible exchange rate and the fixed exchange rate regimen.

To describe the current scenario let’s assume there are two trading blocks, in particular developed markets (DM) and emerging markets (EM). Emerging markets have higher interest rates than developed markets because developed markets were in recession and policy makers decided to “stimulate” their economies. Developed markets have a flexible exchange rate and emerging markets has a fixed exchange rate. 

Following the logic of the Mudell-Fleming model, the increase in monetary supply (quantitative easing QE) will move the liquidity preference curve (LM) to the right decreasing the DM interest rate. The decrease in the DM interest rate make investors prefer to bonds or other assets with higher returns in EMs markets. This net capital outflow produces devaluates the DMs currency boosting their exports. The increase in exports shift  “Invesment and Savings” (IS) curve to the right, generating an increase in the national income. So, following this logic an increase in monetary supply generates a temporal increase in GPD.

On the other hand, EM with a fixed exchange rate will increase their capital inflows attracted by higher interest rates. This new flows will generate a big pressure in the EMs currencies. Central banks in EMs will increase the amount of foreign reserves, generating an increase in the money supply. This increase in the money tends to equate EMs to DMs interest rates while increasing the EMs output.

So, if Emerging Markets, let’s say China has a fixed exchange rate, the DM quantitative easing or any increase in the monetary supply will produce a low interest rate, but the DM currencies will be not depreciated again the Chinese Yuan. Therefore, there is no improvement in the exports and the increase in the monetary supply will not stimulate economic growth. 

From the point of view of DM markets the EMs markets are manipulating the currency prices. From the point of view of EMs the developed markets are manipulating the currency by means on excessive money supply. That explains the antagonic interests between this 2 blocks.

Under this circumstances EM will have more growth, because the increase in development markets money supply is translated in the increase in the EMs supply generating a very politically convenient boom in this economies. 

There are also risks associated with this short- term boom in EMs economies. The generation of inflation or asset bubbles in their economies. EMs markets policy makers have a great temptation to take advantage of the short-term boom despite they know the negative punishment of having inflation or asset bubbles. 

With that framework in mind, we can model those “trade battles” using game theory. We will use the generic games to model games between 2 actors with contradictory interests described in table 2. For instance, we will model 4 kinds of game depending of the payoff of matrix. P=Punishment, S=Sucker Payoff, T=Temptation to defeat payoff, R= Reward.

	EM
DM	No Free Trade	Free Trade 
No Free Trade 	P,P	S,T
Free Trade 	T,S	R,R
Table 2 Game matrix of economical blocks with antagonic intersts









1.	Prisioner’s dilema: T>R>P>S
2.	Hawk-Dove Game: T>R >S>P
3.	Harmonic Game: R> T> S>P
4.	Stag-Hunt Game:  R>T>P>S

Description of the Model


Model 1

In the first model we will assume that the currency wars resemble a prisoner dilemma game. The protectionism measures are a kind of defeat. Allowing international trade is a way of cooperation. International trade allows specialization among countries, one of the drivers of economical growth. In this sense, when both countries allow international trade, they get a better payoff.

In this model international trade is the prisoner’s dilemma tournament among 18 countries. A couple of country meet to trade and apply one of the random strategies.  We would like to study 3 scenarios:

a)	Every country has a free trade bias (probability free trade =0.7).
b)	Every country has a protectionist bias (probability free trade= 0.3)
c)	Scenario based on macro-economical variables. (Table)


We assume would like to study the temporal evolution of pay off as well as the results afters “250” trading days as proxy to the evolution of the GDP.

The measures we consider as protectionism are: capital controls, fixed exchange rates, quotes, trade tariffs, negative interest rates, quantitative easing or any form of printing money. We will focus our attention in three characteristics the countries level of debt/GDP, real interest rates and if the country if highly dependent of commodities exports.


In general with the matlab code you could simulate other scenarios based in the follow strategies:

1.TotalProtectionism 

2. Total Free Trade

3.Imitate the opponent past strategy (Tit for Tat)

4.If once currency control, always currency control (GRIM) 
 
“Fool me once, blame on you Fool me twice, blame on me” Indian proverb

5.Free trade bias (probability free trade 0.7)

6. Protectionist bias (probability free trade 0.3)






 
Table 3 Scenario 3 based on key macroeconomical variables

Model 2

As we said before, the problem with this model is that we assume explicitly that we are facing a game with T>R>P>S (Prisoner’s dilemma). Countries applying tit-for-tat strategies are able to improve the coordination and trust and to transform a multi-agent prisoner’s dilemma into antagonic game between two economical blocks.  This situation is completely different. We can not assume explicitly that the two blocks are facing a prisoner’s dilemma anymore. Indeed, they can face any game of antagonic interests such as Hawk-Dove game, Stag Hunt game, Harmonic game or a prisoner’s dilemma.

In Model 2 we want to understand what are the equilibriums on those games and as well as determine if they are stable or not.  We also focus on having a better understanding of the underlying mechanisms that make this antagonic games to fluctuate between different equilibriums. 

In other to understand those mechanisms we will analyze how   POWER, TRUST AND COORDIANTION modify the system equilibrium.  We reproduce the same results than  (Helbing, 2011). We only change the names to have a more intuitive economical representation. 

We assume the normal anatagonic game matrix between 2 players 

	Player 2
Player 1	Free Trade	No Free Trade
Free Trade	R,R	S,T
No Free trade	T,S	P,P

Definitions: 

C= R-T  (Coordination)

T= S-P  = (Trust)

POWER = f

1.	Prisoner’s dilemma: T>R>P>S
2.	Hawk-Dove Game: T>R >S>P
3.	Harmonic Game: R> T> S>P
4.	Stag-Hunt Game:  R>T>P>S

When a country from one block has the same behavior than a country of other block we called this action as coordinated action. If not, these countries are not cooperative.  We are interesting in modelling the dynamic of the cooperative population in both economical blocks.

With this propose we use the general replicator equation described in (Cressman, 1995), this equation are in term of the game payoffs and the power difference between economical blocks.

   (1)

   (2)






Model 3

This part of the project is the most important individual contribution of the project.  

The question here is about firm’s size. What is the size evolution of firms in every game?  What is the most important growth factor in every scenario? 

In reality every block are constituted by several firms.  In this section we want to show how the different game scenarios of international trade affect the statistical dynamic of firm’s size.

We assume that firms can grow because of two reasons: Economies of scale and scope or by means of cooperation with other partners that leads to innovation and lean processes, we suppose partners are in the other economical block.

Economies of scale and scope are related with return on cost and financial leverage. Therefore this term is related with how much of their assets are invested in R&D, mergers and acquisitions or sales force. To develop economies of scale and scope, companies needs credit by means or issuing bonds or borrowing money from banks. Both of these alternatives depend directly on the firm size. For banks point of view more size more collateral. For debt issuing more size less risk perceived by the market and debt rating agencies.

The other source of economical growth is cooperation with suppliers and customers that lead to cooperative innovation and lean process. This depend of much of the assets are invested in joint ventures, integration with suppliers and customer, marketing etc.

In model 3 we use the population of cooperators in every block derived from model 2 as the density of cooperation in every economical block.

From a financial management point of view, we now that return on equity (ROE) of a company depends on 3 factors, return on sales (ROS), capital turn over (CT) and financial leverage (FL).

ROE= ROS*CT*FL.

We model that ROS and FL are related with company size by the reasons we explain above.  While capital turnover are related with how much the companies is able to integrate with customers and supplier that n some way could be translated in term of lean processes and lean management.

  (3)
                  ROS*FL                                 CT
             Economies of                  Interaction with suppliers
           Scale and Scope                      and customers

           

  (4)
            Economies of      Interaction with suppliers
           Scale and Scope             and customers




Where
   and no correlated.

P= Density of cooperative countries in developed markets 

Q= Density of cooperative countries in emerging markets.

 = Firm’s size in Developed Market Block

 = Firm’s size in Emerging Market Block

N= Number of firms in Developed Markets

M=Number of firms in Emerging Markets 


The intuition of the model is simple, if there is no-cooperation between blocks we assume all the firms in every block are cooperative inside the block so the return is multiplicative by the numbers of firms inside the block. If there are cooperative with the other block, P and Q determines the density of cooperation in every block, so the multiplicative effect is   depending on the block.






Implementation


Iterated currencies war functions:


%% Runs an ICW (Iterated Curency war) 
% Countries  with different strategies iteratedtly face each others and decide
% to be proteccionist or having free trade policies.

% Strategies  have menory and based in the past behavior

printf('\nStart the tournament...\n');
R=200; % number of trading days

%% PLAYERS & STRATEGIES
% Set up 4 players and assign them different strategies
% 1 always proteccionism
% 2 always free trade
% 3 Currency control of the other do the same
% 4 GRIM if once currency control always currency control
% 5 Random 0.5 Proteccionsim
% 6 Random 0.7 Proteccionsim
Q=[1,2,3,4,5,6];
n=length(Q);

%% MATRIX PAYOFF

% We assume the payoff the total surplus of free trade, is 
% higher than tempation to proteccionism 3+3 > 5+0

bothProteccionsit = 1;
bothFreeTrade = 3;
temptationToproteccionism = 5;
ProteccionistPayoff = 0;

payoffMatrix = [bothProteccionsit,Proteccionsit;
                temptationToProteccionsit,bothFreetrade]

%% START CURRENCY WAR
%
Z=zeros(n,n); % Currency war table

for i=1:n
    for j=1:n
        [hC1,hC2,GDPC1,GDPC2 ]=iteratedcw(R,Q(i),Q(j),payoffMatrix);
        Z(i,j)=scoreGDPC1; 
    end
end


%% PRINT RESULTS
%
display(Z);
scores = zeros(n,1);
for i=1:n
    scores(i)=sum(Z(i,1:n));
end
display(scores);

imagesc(Z);

% Who wins?
% Why?


Auxiliary Functions

function x=trade(player,opp,strategy) 
 
if (strategy == 1) %always protectionism
    x=0;
    
elseif (strategy == 2) %always free trade
    x=1;
    
elseif(strategy==3) %Currency control for Currency control (titfortat)
    if(isempty(opp))
        x=1; % Be nice first
    else
        x=opp(length(opp)); % Repeat last opponent's trade
    end
    
elseif(strategy==4) %GRIM
    threshold=0.9;
    s1=rand(1,1);
    if(isempty(opp)) && s1<threshold % Be nice first randomly probability 0.9
        x=1;
    elseif (isempty(opp)) && s1>=threshold
        x=1;
    else
        if(sum(opp)<length(opp)) && s1<threshold % After one protectionism,protectionism
                                                 % always with probability
                                                 % 0.95
            x=0;
        else
            x=1;
        end
    end
 
else % random  free trader , and protecctionist trader
    s=rand(1,1);
    
    if (strategy==5)
        threshold = 0.35;
    else
        threshold = 0.65;
    end
    
    if(s<threshold)
        x=0;
    else
        x=1;
    end
end


%% Itereaded currency war based on prisioner dilema
% Returns four arguments: the two lists of strategies (0= Protectionism, 1= Free Trade)
% and the two GDPs and the acumualated GDP. 
 
function [X,Y,XGDP,YGDP]=iteratedcw(r,c1strat,c2strat,payoff)
 
% Init
mProtectionism=payoff(1,1);
mFreeTrade=payoff(2,2);
protecctionistlose=payoff(1,2);
protectionismwin=payoff(2,1);
 
X=[];
Y=[];
XGDP=0;
YGDP=0;
AcumXGDP=[];
AcumYGDP=[];
 
for i=1:r
 
    % Determine the next move based on the trading story
    newX=trade(X,Y,c1strat);
    newY=trade(Y,X,c2strat);
 
    % Add the last trade
    X=[X,newX];
    Y=[Y,newY];
 
    % Update the GDP
    if (newX==0) %Country1 protectionism
        if(newY==0)
            XGDP=XGDP+mProtectionism;
            YGDP=YGDP+mProtectionism;
            
        else
            XGDP=XGDP+protectionismwin;
            YGDP=YGDP+protecctionistlose;
        end
    else % Country1 Free Trade
        if(newY==0)
            XGDP=XGDP+protecctionistlose;
            YGDP=YGDP+protectionismwin;
        else
            XGDP=XGDP+mFreeTrade;
            YGDP=YGDP+mFreeTrade;
        end
    end
   
end
end

POWER LAW SIMULATIONS

%%POWER LAW SIMULATIONS
%% Equilibrium  P=0.2,Q=0.3   COEXISITENCE EQUILIBRIUM or Bistability
 
P=0.4;
Q=0.5;
M=1000; % Number of firms in emerging markets block
N=1000; % Number of firms in Developed markets block
 
X=10*ones(1000,1000);
 
 for i=2:1000;
     for j=2 :1000
     X(i,j)= ((1+0.0001*randn(1,1))^((1-P)*N))*((1+0.0001*randn(1,1))^(P*M))*((1+0.0001*randn(1,1))^(Q*N))*X(i-1,j);
     end
 end
 
 
 
%%% Equilibrium P=0, Q=1   (Develop markets dominates) 
 
P=0;
Q=1;
M=1000; % Number of firms in emerging markets block
N=1000; % Number of firms in Developed markets block
 
 X2=10*ones(1000,1000);
 
 for i=2:1000;
     for j=2 :1000
     X2(i,j)= (1+0.0001*randn(1,1))^((1-P)*N)*((1+0.0001*randn(1,1))^(Q*M))*X2(i-1,j);
     end
 end
 
 
 
% Equilibrium P=1, Q=0 (Emerging Markets dominates)
  
P=1;
Q=0;
M=1000; % Number of firms in emerging markets block
N=1000; % Number of firms in Developed markets block
 
 X3=10*ones(1000,1000);
 
 for i=2:1000;
     for j=2 :1000
     X3(i,j)= ((1+0.0001*randn(1,1))^(P*N))*X3(i-1,j);
     end
 end
 
 
 
% Equilibrium P=0 , Q=0;  (Currency War)
P=0;
Q=0;
M=1000; % Number of firms in emerging markets block
N=1000; % Number of firms in Developed markets block
 
X4=10*ones(1000,1000);
 
for i=2:1000;
     for j=2 :1000
     X4(i,j)= (1+0.0001*randn(1,1))^((1-P)*N)*X4(i-1,j);
     end
end
 
 
%%% Equilibrium P=1, Q=1; (Emergence of international trade standard)
 
 
P=1;
Q=1;
M=1000; % Number of firms in emerging markets block
N=1000; % Number of firms in Developed markets block
 
X5=10*ones(1000,1000);
 
for i=2:1000;
     for j=2 :1000
     X5(i,j)= ((1+0.0001*randn(1,1))^(P*N))*((1+0.0001*randn(1,1))^(Q*M))*X5(i-1,j);
     end
end
 
 
 %%%%% Ploting
 
 
 
 
 loglog(sort(X(500,:)/min(X(500,:)),2),sort(1-(cumsum(hist(X(500,:),1000)))/1000,1),'*r')
 hold on;
 loglog(sort(X2(500,:)/min(X2(500,:)),2),sort(1-(cumsum(hist(X2(500,:),1000)))/1000,1),'ob')
 loglog(sort(X3(500,:)/min(X3(500,:)),2),sort(1-(cumsum(hist(X3(500,:),1000)))/1000,1),'^k')
 loglog(sort(X5(500,:)/min(X5(500,:)),2),sort(1-(cumsum(hist(X5(500,:),1000)))/1000,1),'+g')
 
 
 %%%% Calculate Alpha
 
[alpha, xmin, L]= plfit(X3(500,:))


VIDEOS CODE:

%%%%% Video Hawk-Dove Dynamic
C=[-0.2:-0.05:-4];
T=[0.1:0.05:5];
N=length(C);
% Get the handle of the figure
h= figure();
%%%%% STANG AND HUNT CHANGE IN POWER (F) C=3 T=-2
C=3;
T=-2;
F=0.1:0.01:0.9;
N=length(F);
% Get the handle of the figure
h= figure();
% Prepare the new file.
aviobj= avifile('CURRENCY WARS STAG-HUNT Power Variable.avi');
for i=1:N;
z=10*ones(21,21);
[x,y]=meshgrid(0:.05:1,0:.05:1);
dy  = y*(1-y)*(T*F(i)+(C-T)*F(i)*y+C*(1-F(i))+(T-C)*(1-F(i))*x);
dx =  x*(1-x)*(T*(1-F(i))+ C*F(i)+(C-T)*(1-F(i))*x+(T-C)*F(i)*y);
dyu = dy./sqrt(dx.^2+dy.^2);
dxu = dx./sqrt(dx.^2+dy.^2);
imagesc(0:.05:1,0:.05:1,z)
colormap(gray)
hold on;
quiver(x,y,dxu,dyu)
hold off;
title(['STAG AND HUNT T= -2',' C=3 ',' F= ',num2str(F(i))])
ylabel('PROPORTION OF COOPERTIVE PRINTERS ')
xlabel('PROPORTION OF COOPERATIVE CURRENCY CONTROLERS')
Frame = getframe(h);
aviobj = addframe(aviobj,Frame);
end
close(h)
aviobj = close(aviobj);

Simulation Results and Discussion

MODEL 1


When countries have a free trade bias the total GDP is high and is distributed randomly around the 18 countries. In some way every body wins. (Figure 1) When they have a protectionism bias the have a lower output and every body lose. (Figure 2)

When countries apply learning strategies like tit for that the system found other solution. Economical blocks emerges form this strategies. In particular, commodities exporters find a way to cooperate with country with low of debt. This block will outperform countries with high levels of debt over GDP. (Figure 3)

This result is according with common economical blocks we observe in 2012, BRICS, DEVELOP MARKETS (DM). Inside BRICS  (EM) are very different “animals” for instance China and India have very different productive processes than Brazil and Russia but given the scenario where DM always print money applying tit-for-tat strategies BRICS countries find a path for coordination.  This changes the bargaining power of the BRICS as block and could transform the prisoner’s dilemma in a Stag-Hunt game or Haw and Dove game.   

 
Figure  1 Countries playing an iterated prisoner's dilemma with a free trade bias (cooperative bias)
 
Figure  2 Countries playing an iterated prisoner's dilemma with a protectionism bias (Defeat Bias)
 
Figure  3 Emergence of blocks using tit for tat strategies


There are 4 videos attached to the presentation were we can observe the diffents equilibrium in particular for the Hawk and Dove and the Stag-Hunt game .We show how the Nash equilibrium changes in both games depending on the values of trust an confidence.

The harmonic game exist a trading norm and one of the behavior predominate over the others.
MODEL 2


In this model we replicate the results obtained by (Helbing, 2011). We present 4 different antagonic games and we are interested in identify the possible equilibrium and their stability.

There are 5 kinds of equilibrium, the combination:
1.)	P=1,Q=1 Emergence of a trade standard
2.)	P=1,Q=0 Emerging Markets win, its trading norm is dominant.
3.)	P=0, Q=1Developed Markets win its trading norm is dominant.
4.)	P=0, Q=0 Currency war no body wins, no body cooperates.
5.)	P=a, Q=b Coexistence of international trade system.

The 5th equilibrium is very interesting in the sense it allows the 2 different trade systems to coexist. This equilibrium is present in 2 games. The stag-hunt game where the equilibrium is unstable and the hawk-dove game when the coexistence state is stable.  

 HAWK-DOVE GAME


It is scenario with high trust but difficult coordination. This game has three Nash equilibriums but the only evolutive stable is the coexistence state. We show in our simulation of the vector field around the equilibrium. (Figure 4) (CURRENCY WARS HAWK-DOVE Variable Power.avi)  

Conclusion: Difference in power in a scenario of trust but difficult coordination will generate a currency war. (In the video is clear the influence of the power differential)

STAG-HUNT GAME

In the Stag and Hunt scenario incentives are aligned R-T>0, therefore it is possible to have a coordinated action. The problem here is that there is no trust S-P<=0 .In this game exists 3 Nash equilibriums one of currency system is accepted by the other block. The co-existence is an unstable equilibrium in this game. In this scenario difference in power generates a currency system that both blocks accepts. (Figure 4)

Conclusion: In a scenario of easy coordination but no trust, power differences will create a dominant currency system. (CURRENCY WARS STAG-HUNT Variable Power.avi)

PRISONER’S DILEMMA

It is a scenario where there is no trust and coordination is difficult. The game converges to a no cooperation state Q=0, P=0 (Figure 4)

HARMONIC GAME

It is a scenario where there is trust and coordination. The game converges to a no cooperation the emergence of a standard or international trade norm Q=1, P=1. (Figure 4)




 
Figure  4 Currency wars possible antagonic games, attractors and repulsors.



MODEL 3


In this model we are interested in understand the dynamic of firms the dynamic possible equilibriums.


PRISONER’S DILEMMA

Economical blocks are facing a prisoner’s dilemma scenario theare no cooperative countries in any block. Q=0, P=0

So rewriting equation (3) and (4) we will have:

  (5)




If n and m are large enough this equation converges to a power law of exponet  of maximum likelihood =2,019.
  

Case 2 Stag-Hunt Game (Bi-stability)

a) If P=0 and Q=1, the emerging markets firm’s size follows a power law exponent close to one, and the developed markets a power with exponent of maximun likelihood of 1.9161.

   (6)

b) If P=1 and Q=0, the emerging markets firm’s size follows a power law exponent close to 2 and the developed markets a power with exponent of maximun likelihood of 1.9161.


     (7)





Case 3 Hawk-Dove Game   (Coexistence)

If P=a and Q=b   our equation have the follow form:


  (8)


In this game has 3 equilibriums, 2 in pure strategies and one in mixed strategies, the only evolutionary stable equilibrium is the coexistece case for P=0,5 and Q= 0.4 we get a power law with exponet with maximun likelihood =2.1702


Case 4 Harmonic Game    (Emergence of a norm)



If P=1 and Q=1 the size equation have the following form:

  (9)



The size distribution  follows a power law and the coefficient  of maximum likelihood is 1,5158

 
Figure  5 Power law distribution in the different equilibrium. Alpha calculation based on the Kolmogorov test using http://www.santafe.edu/~aaronc/powerlaws/ (Santa Fe Insitute)


Summary and Outlook 


In this project we find that countries that are facing an antagonic games converges to two currency blocks when they apply tit-for-tat strategies.

The second step was to find the equilibrium states of the games that resemble a confrontation of two blocks with antagonic interests. We found 5 possible equilibria: both blocks win, one of them wins, all lose, or both coexist.  The equilibrium’s convergence depends on the level of trust and coordination. In a situation where coordination is possible but there is no trust the coexistence state is unstable. On the other hand, in situations when there is trust but coordination is difficult coexistence is stable.

In the final part we prove that in the currency war state and coexistence states the asymmetry in firm size is higher than in the other states. It shows that no free trade measures tend to form oligopolies or national champions in the protectionist blocks. Firm’s size probability distribution follows different power laws depending on the equilibrium.

For future research I am interested in link this model with empirical macro-economical data. It would be also interesting to model what happen if the society in every block is also polarized and how it alters the firm’s size distribution.

References


Cressman, R. (1995). Evolutionary game theory with two groups of individuals games an economic behavior. 11, 237-253.
Helbing, J. (2011). Cooperation, Norm and Revolutions : A unified game-theoretical approach. PlosOne .
Santa Fe Insitute. (s.f.). Power Laws. Obtenido de http://www.santafe.edu/~aaronc/powerlaws/
Sornette, S. M. (August de 2008). Theory of Zipf's Law and General Power Distributions with gibrart law of proportional growth.
Weibull, J. (1995). Evolutionary Game Theory. Cambridge, MA: MIT press.
Wikipedia. (s.f.). Kontratiev Wave. Obtenido de http://en.wikipedia.org/wiki/Kondratiev_wave
Wikipedia. (s.f.). Mundell Fleming Model. Obtenido de http://en.wikipedia.org/wiki/Mundell–Fleming_model

