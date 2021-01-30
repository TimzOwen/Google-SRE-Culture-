
## Site Reliability Engineering 
#### SRE & DevOPs

__DevOPs__ is a combination on **Developers** + __Operators__

#### Functions of DevOPss

1. Reduce Organization's Silos

2. Accept Failure (Blamelessness)

3. Implement Gradual Change (Deployment velocity)

4. Leverage tooling and automation (Toil automation)

5. Measure everything (measure Toil and Reliability)

__SRE__ :

    The pratice of balacing between velocity of deployment and Reliability Risk

    plays a Role and Practice to maintain and make sure services are running and meeting customer's needs
    Focus on practices  and technical and practical traditions

### Service Level Objective (SLO)

#### Value of SRE:

__Mission SRE__: To protect,provide for,and progress s/w and systems with consistent focus on availability,
                latency, perfomance and capacity

#### Accepting Failures as normal with blameless postmoterms 

Be comfortabe with __Failures__

Eliminate ambiguity in __monitoring__

Establish and document __process__



#### Components of Postmoterm:

__Details__ of the incident and timeline

The __Actions taken to mitigate__ or __resolve__ the issue/incident

The incident's __impact__

its __trigger and root cause__ or causes 

The __follow up actions__ to prevent it's reoccurence

__Postmoterm__ ensures that al __root causes are understood__ by the team

Reduces likelihood for stressful outages

avoid multuplying complexity

Learn from mistakes and those from others

#### Blamelessness and Psychological safety

__Psychological safety__: Beleif that a person will not be punished/humuliated for
    speaking up with ideas, concerns or mistakes

#### Building psychological safety:

    1. Frame work as learning Problem and not an execution problem
    2. Acknowldge your own fallibility
    3. Model curiosity

#### impacts of psychological safety: (on Leadtime,deployment frequency & time to restore)

    Cooperation is high
    Bridging is encouraged
    Messengers are no punished when delivering bad news
    Failure is treated as opportunity for improvement
    New ideas are welcomed

#### BLAMELESSNESS

This is a behaviour that __fosters__ psychological safety

__Why people blame: 

    Hindsight bias (Tendency of overestimating one's abilit to predicted/unpredicted outcome)
    discomfort discharge (when people blame others to discharge discomfort at a neighboring level)
 
 __Focus on systems and Processes __not__ People__

 Innovations require some risk taking 
 
 
### Reducing organizational SILO

There is shared owenership between development and operations team

building pillars:

    Error budgets
    SLO (Service Level objective)

Reliability = __GoodTime__/__totalTime__ => (__Fraction of the time the service is available and working__)

Realiability (sophisticated approach):

    GoodInteraction/Total interactions => Fractions of users who experience a service working and available

__ERROR BUDGET__ : amount of unreliability you are willing to tolerate

__SLOs__ Precise numerical target for systems 

__SLIs__:(Service-Level Indicators) How well your system is doing at any moment in time

        goodEvents/ValidEvents x 100

        Map to user expectations 
__SLA__(Serice Level Agreement) : Promise about your health of service ot your customers.


### Unifying Vision,Foster Collaboration & Share Knowledge:

SRE Culture Focus:

    Creating a unifed Vision
        Team Vison statement
        Support company's vision
        Values,Purpose,Mission, Strategy ang Goals
        
            Values:
                your response to others
                your commitment
                How you spend your time
                the way you operate as a team
                
            Purpose:
                Explains Why it exists
                improve life and work satisfaction
                Reduce conflits
                Creates greater team connections
                
            Mission:
                This is a clear and compelling goal the team wants to achieve
                
            Strategy:
                This is how your team will realize its mission
                    can be leverage
                    can be single initiative
                    Might require change
                Building  blocks:
                
    Determine what collaboration look like
    Share knowldge among teams

#### Make tommorow better than today

    Continuos integration/ Continuos Delivery (CI/CD)
    Canarying
    Toil
    Automation


### CI/CD

CI: Building, Integration, and testing code within development environment

CD: Deploying to production frequently or at the rate the business chooses 

__Software as a Process__: 

    Code 
    Build
    Integrate
    Test
    Release
    Deploy 
    Operate

__Canarying__ : Deployment pattern that allows you to roll out changes or new features to a subset of users

#### Desing Thinking and Prototyping:

Combining creativity and Structure to complex problems

Process:

    Empathize
    Define
    Ideate
    Prototype
    Test

#### Toil Automation:

Toil are manual and repeatitive work

can lead to slowdown ,precedence, stagnation, low morale , confusion, slow progress, Attrition,breach of Faith 

__Automation__:

    Consistency
    A platform that works on more systems and quick tasks execution
    Quicker Resolutions
    Faster Action
    Time saving

### Psychology of Change and Resistance

    Navigators
    Critics
    Victims
    Bystanders

__Emotional response to change__

    Denial 
    Reistance
    Acceptance
    Exploration
    Commitment 
    Growth

### Regulating workload

Areas covered:

    Measure Realibilty and Toil
    Monitoring
    Goal-setting, Transparency, and data driven decision making

#### Measure everything by qualifying toil and Reliability

Measure Reliability

    Choose good SLIs
    
Measure Toil

    Identify it
    select unit of measure
    Track measurement continously 
    
Monitoring

    Gain visibility into system

__Signals to measure__:

    Latency 
    Traffic
    Errors
    Saturatoin

### Goal Setting , Transparency and Data-based decision Making

Goal Setting

    use OKR grading  (60-70)

Transparency:

    how trustwothy you perfom a task and deliver it
    Have feedback look

Data driven decision making 

    remove biasness
    always question impressions
    make decisions colletively



