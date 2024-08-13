# 16-Data-Governance

What Is Data Governance?
As a data professional, some of the most frustrating conversations you will have about data governance
will be about data programs feeling like a series of constraints versus a strategic enabler and that you
are slowing business down vs. enabling excellence. Having led data transformations in three Fortune
500 companies, I have heard my fair share of these same messages. In my humble opinion, this is
feedback; feedback that we are speaking in “data speak” and have not created a business case that is
centered on value generation from the lens of our stakeholders. Rather, we have delivered a business
case that is focused on data needs vs. business needs.
From a stakeholder’s perspective, there are a plethora of forces at stake in driving business: generating
revenue through the sales teams, marketing to existing and potential customers, economic factors,
and supply chain challenges. Data is a part of all of these critical business components, but it is not
the first thing that comes to mind for our stakeholders. It is embedded in how business runs. It is a
part of the day-to-day. It does not and should not feel like a standalone function.
Therefore, it’s our job to serve the business and to make it feel seamless to the business stakeholders
we enable. When things feel like friction, it’s not necessarily because we’re not supported; it’s because
we are one of many problems leaders are facing. Often, this comes in the form of a lack of buy-in
or pushback, a seemingly endless number of questions, or simply a lack of engagement. For data
professionals, conversations like this often end in frustration and the underfunding of the data
governance program. I have seen this scenario over and over again in organizations firsthand and
have heard it from data executives in every single industry. Far too often, it ultimately ends in the
failure of a chief data & analytics officer to survive in the organization.
The question is, why?
Over the course of the next 17 chapters, I will explain why Chief Data and Analytics Officers fail to
establish themselves as strategic business partners in their organizations and how you can overcome
these common pitfalls and succeed. I will cover everything you need to know to build a case for
data governance, rally your organization to support you, deploy a strong data governance program,
leverage core data governance solutions, and apply all of this in a case study for a fictitious financial
institution. Let’s dive in.4 What Is Data Governance?
What you can expect to learn
Throughout this book, I promise to be transparent and direct about my experiences, and we’re going
to start strong: governance programs fail because we have failed. We have failed to explain data
governance in a way that makes sense to our business stakeholders. We have failed to deeply and
intimately understand how our solutions will drive business success. In short, we have failed to explain
in terms of business value. Conversely, the most successful data executives I have had the opportunity
to work with have been successful because they deeply understand their company. They have spent the
time to intimately understand the business, have crafted data solutions that enable business success
and have successfully explained the benefits in terms of business results vs. data results.
As we go deep into these topics, I will not make assumptions about your experience implementing a
successful data governance program. I will start with the basics by grounding you in definitions and
the foundational capabilities and will build on how to launch a successful and impactful program,
complete with the measures for success that will resonate with executive management and, ultimately,
the board of directors for your organization. In the end, we will complete a case study to bring it all
together. By the end of this book, you will have all you need to launch a program and deliver with
excellence in your own organization. No longer will your organization be overwhelmed by data and
underwhelmed by insight. We will change the narrative together.
In this chapter, we will ground ourselves in the basics of data governance and how it relates to adjacent
capabilities. Then, we will define the components of a data governance program, why each component
matters, and why we treat data governance as an enabler for business value. Subsequent chapters will dive
deeper into the fundamental capabilities of a data governance program and how to implement them.
We will cover the following main topics:
• What is data governance?
• What’s driving the increasing need for data governance?
• A brief overview of the data governance components
• Data governance as a strategic enabler
• Building a business case for your company
• When and why to launch a data governance program
What’s driving the increasing need for data governance?
As I meet with data professionals across industries, it is abundantly clear that data governance is more
important than ever. Executives are expecting more from data, but without the proper investment, it
is harder than ever to respond at the speed of business.What is data governance? 5
So why is it increasingly difficult to respond to our executives at the pace of the business? There are
a number of key factors, including the continuous rise in the following:
• Data volume: We have more data today than yesterday (everyday!). In fact, the amount of data
doubles every two years. Yet, we cannot expect to double our efforts or double our staffing or
technology spend.
• Regulation: The regulatory landscape is evolving, increasing expectations for how data is
handled. In the United States, at the time of this writing, six states had signed privacy and data
protection legislation into law. This increases the complexity of compliance for data handling.
• Expectations: Executives’ expectations are rising, but our use of data is not. In a recent Tableau
survey, >80% of CEOs wanted their organizations to be data driven, but less than 35% percent
of employees felt their data was used in decision making.
• User base: More individuals than ever are engaging in data, wanting it for their own use but
needing to trust it. It puts our governance professionals in a position to add tremendous value
by providing trusted, well-governed data to our organizations.
We have to become more innovative and more embedded, leveraging more technologies (e.g.,
automation and AI) than ever before. We talk about what that means for our customers. But what
does it mean for us? If it’s difficult to answer key, basic business questions today, how do we expect
to do it in two–three years with more data than ever? We must take this sense of urgency and build
capabilities that will scale and last as our volume, complexity, expectations, and user base continue
to grow at an unprecedented rate.
What is data governance?
Before we dive in, it’s important that we ground ourselves in basic definitions. During my first role in
data management, we made the mistake of assuming that our stakeholders around the organization
were aligned on what data we were referring to when we were discussing a particular domain of data.
After several months of having difficult conversations on scope (if a particular data element, report,
or system were in scope), we realized that we needed to go back and ground all stakeholders in a few
very simple questions.
Data governance is the formal orchestration of people, processes, and technology by which an
organization brings together the right data at the right time with the right controls to enable the
company to drive efficient and effective business results. This formal orchestration should control,
protect, deliver, and further enhance the value of data and create equity for an organization. Data
governance is active and is delivered through capabilities, including the following:
• Metadata management
• Data lineage
• Data quality6 What Is Data Governance?
• Data architecture
• Mastering data
• Data operations
We will explore these core capabilities, among other methods, in detail in subsequent chapters. The
capabilities that make up a successful data governance program are defined slightly differently in just
about every organization. Therefore, it is important that we define them here for the purposes of this
book. Feel free to use the vocabulary in this text within your organization or the common language
of your business.
Important note
Take the time to build a quick reference guide that defines the most basic terms used around
your data governance program (e.g., data, governance, metadata, and so on). Make it accessible
to the whole organization as a quick reference guide. Add to it as needed.
Data versus information
I want to point out that there is a passion for the use of data versus information terminology among
industry veterans. Some practitioners are firm in their beliefs that these terms are not the same and
should not be used interchangeably. Others use them synonymously without much thought. In my
humble opinion, either can be appropriate for your organization. The important point is to distinguish
between the two so that your organization understands the definitions and how to use them appropriately
in your organization. Personally, I do not believe either position is correct or incorrect. It is far more
important that you meet your stakeholders where they are and that your organization agrees on the
alignment you choose to use. For the purpose of this book, I will use the term “data” primarily, and I
will be sure to be specific about what that means.
Use case – financial services company
In my very first data governance position, we launched a robust and multi-million dollar transformation
to comply with a regulatory requirement around data management and regulatory reporting. About
six months into the effort, we found we were really struggling to define what was “in” vs. “out” of the
scope of the program. After several curricular and passionate conversations, we learned that we were
not able to scope well because, ultimately, our stakeholders had differing views about what constituted
“data” vs. “metrics.” We ended up building a full-blown methodology to ground the company and our
regulators on how we thought about the reports so as to be in scope, built a full list of all reports, and
documented whether each one either met the criteria or did not meet the criteria, and this was to be
available for a credible challenge to anyone or any group interested. Instead of debating it theoretically,
we documented the criteria with specificity and then clearly articulated the justification.What is data governance? 7
What I learned in this experience was two-fold: you cannot make assumptions regarding what people
know or don’t know when scoping a data program, and that you must have grounding definitions that
can be socialized, agreed to, and documented so that all involved could remain grounded.
I’ll ask us to do the same throughout this book. Please come back to these definitions as needed so
we can be aligned.
What data governance is not
Too often, companies have a tendency to blame problems on the data and/or the data team. Data
governance (team or program) is not the solution to every problem. Data, like air, is everywhere in
an organization, and it truly takes the entire organization to manage it well. Similar to the quality of
air when a fire breaks out, poor data moves through an organization like smoke moves from a fire.
The strong management of data requires prevention, detection, and correction, and to manage data
well requires the entire company to be on board. A single data team cannot unilaterally solve every
data problem. It will take the involvement and action of the organization at large to drive change and
manage data effectively.
Secondly, data will never be perfect. If you or your executive team is expecting perfection from data
governance, I would urge you to adjust your expectations. To ensure we align on what the appropriate
expectations and objectives of a successful data governance program are, we must define success. To
do that, we must start with the objective of data governance.
The objective of data governance – create business value
To put it simply, companies exist to increase value for stakeholders. When it comes to data, there is
one very important objective of data to increase equity for stakeholders. Managing data effectively is
one of the ways companies can increase value for their organization.
Figure 1.1 – A simple value equation
An asset is something of economic value that is owned by an organization. A liability is an obligation
(either current or future) that decreases the overall value of the organization. Thus, when assets minus
liabilities result in a positive value, the organization has an increase in value (i.e., has created equity),
whereas when assets minus liabilities results in a negative value, the organization has a decrease in
value (i.e., has reduced equity).8 What Is Data Governance?
The same mindset can be applied to data. Data can impact equity in a number of ways. Equity can be
created through addressing and minimizing operational risks by sustaining regulatory compliance,
avoiding fines and penalties, and increasing or creating revenue. I break this concept down into two
key subcomponents to manage data governance more specifically. These two subcomponents (assets
and liabilities) are directly influenced by my formal training as an accountant and IT auditor, and this
tends to resonate well with management when they translate data solutions into measurable value
(ideally, monetary value, but may also consider the time value of employees).
Important note
Data is an asset when it creates value for the organization.
A few examples include:
• Curated datasets that are used for multiple purposes
• Customer health scoring
• An authorized provisioning point
• A data model used for predictive modeling
Important note
Data is a liability when it creates risk for the organization. Data can be both of these things but
cannot be either (for example, a data solution may create value and reduce risk).
A few examples include:
• Non-cataloged data
• Data that has not been classified and, therefore, not appropriately secured
• Data leaks/breached data
Ideally, organizations should manage the liability of data while maximizing data as a strategic asset,
such that data equity is created. Depending on your business and the maturity of your data governance
practices, either asset management or liability management may be a bigger priority.
Data governance should create data equity by increasing the value of data as an asset and minimizing
data liabilities. I encourage you to come back to this framing as you apply the principles in this book
to your own organization. As you pitch data solutions, consider this:
How is this solution increasing the value of my data (increasing the asset) and/or decreasing
the liability?What is data governance? 9
Both are of value. The momentum created by delivery should translate directly to an increase in data
equity over time.
An example of a data asset might be a curated dataset that is reliable because it has clear ownership, is
of high quality, and can be leveraged for multiple business purposes organization-wide. An example
of a data liability might be as simple as an organization not knowing what data it has, where it lives,
or what to do with it. This carries a risk to the company from a security perspective, but also, the lack
of accountability means that individuals may be using the data inappropriately for decisions that it is
not fit for, increasing the company’s risk of making a decision that it shouldn’t be based on data that
were never intended to be used for that particular purpose.
The measurement of the value of an asset is unique to each organization, but in short, being able to
tie back the impact to the organization is a good guiding principle. The following are a few example
questions to consider as you attempt to value the data asset:
• Does this asset enable additional revenue? How much?
• Does this asset save time? Can you calculate the hours saved by an hourly rate for an individual
to calculate the person-hours saved?
• Does this asset improve customer satisfaction? Can this satisfaction be translated or calculated
into value for the organization in terms of additional spending or increased customer retention?
Figure 1.2 – Data assets, liabilities, and equity formula
Data assets may provide value across these components, and value should be calculated accordingly.
The most important part of this valuation exercise is not the calculation itself; rather, it is the alignment
and agreement with the business. Once you have calculated the value, it is important to go to the
business and ask for their feedback. Do they agree with your assessment? If yes, then you have a fully
vetted value for your data asset. If not, work with the business to iterate on your data asset valuation
until you reach an agreement. If you skip this important step (vetting the value), data teams often are
seen to be overselling their value to the organization. This immediately undermines your credibility
in the organization. Agreeing on the value of the business supports a strong business relationship and
provides credibility of past success when seeking future investment into data solutions.
The measure of the liability portion of the equation is of equal importance. Like data assets, the
measurement of the liability carried by an organization’s data will vary based on your organization.10 What Is Data Governance?
Important note
It is not as simple as more data equals more liability.
Rather, the less the data is managed, the higher the liability. When data is unmanaged, the risk
to the organization is higher.
A great example is security risk. When an organization does not understand where data is, it cannot
effectively or adequately protect it. This comes at a high risk (liability) to the organization and could
result in a data leak or, worse, a data breach. Here are a few questions to consider when calculating
your organization’s data liability:
• Do data liabilities increase the risk to the organization? How much? Are there fines or regulatory
penalties we could be subjected to as a result of this liability?
• Does liability drive inefficiencies in our business? Can you calculate the hours incurred by an
hourly rate for an individual to calculate the person-hours impacted due to the inefficiency
(for example, a manual process vs. an automated one)?
• Does this liability impact customer satisfaction? Can this satisfaction be translated or calculated
into a decrease in value for the organization in terms of additional spending or decreased
customer attrition?
Once you have assessed your data asset value and data liability value, you can apply this to calculate data
equity. The idea is to increase the equity over time. This initial calculation can serve as your baseline
by which to calculate progress over time. Organizations also may like to leverage a data maturity
model to measure progress; however, these models can be interpreted widely in an organization and
do not take into account the business value associated with data solutions. Instead, they focus on the
development of data capabilities, which do not always translate well for executive management. I
prefer to focus on business value rather than an organization vs. a maturity model.
We will not dive into data monetization efforts in this book. The economics of the monetization of
data is expertly described in Doug Laney’s book, Infonomics, and I would highly recommend his book
to anyone looking to dive into the monetization of data further.
A brief overview of the data governance components
Now that we have classified data solutions into assets and liabilities and defined how to calculate value,
let’s dive into the components in further detail. I prefer to group the components of data governance
into building blocks. The reason I prefer this approach and have leveraged this framing in several
companies is because it allows the organization to directly tie each building block to specific and
straightforward outcomes. The first building block, policy and standards, is relatively basic and can be
designed with a small team. This is a great place to get started in developing a data governance program.A brief overview of the data governance components 11
Policy and standards
The purpose of this building block is to define data ownership and the structures needed to design
accountability to manage your organization’s data as an asset. This building block will ensure effective,
sustainable, and standardized data governance on which the company can depend. This building
block is a prerequisite for future building blocks because it defines what is required to drive effective
data governance and who needs to be involved. Additionally, the components of this building block
can be created in a simplified way and can be expanded as the company matures in its data journey.
An easy place to start is to draft a simple and straightforward data governance policy. The purpose of
a data governance policy is to tell the company what they need to do, why, and who is accountable.
The objectives of a strong data policy include the following:
• Establishing a single policy and set of standards for data management
• Establish the capabilities and data assets that are in scope for the policy and, in turn, for the
office of the Chief Data and Analytics Officer
• Define the accountability and responsibilities for the implementation of the policy and the
operationalization of data management capabilities
• Set minimum standards for data management, specifically for governance, quality, and metaand master data management
• Define the procedures and usage requirements for tools to drive the consistent and robust
adoption of minimum standards in a consistent manner
• Enable flexibility where appropriate to allow for ease of implementation where possible
• Define what is out of the scope of the policy
As with any policy, it is important to identify the owner of the data governance policy, who will
be accountable for managing the policy by refreshing it at least annually, updating the content,
and evangelizing it to the company. It is also the owner’s responsibility to ensure buy-in from key
stakeholders across the company. Ideally, this owner would be a chief data officer, head of data
governance, or similar role. If your company does not have a data leader in the role yet, another option
would be a chief information officer, chief information security officer, chief privacy officer, or
even a general council.
A policy does not need to be lengthy to be effective. Ideally, the policy would set forth the basics and
would be supported by more specific and topically focused data standards. This approach often allows
the policy to go through a more formalized corporate governance approval process while allowing for
slightly easier updates to the data standards as your organization matures. I recommend implementing
a data standard for each of the core capabilities addressed in Part 2 of this book, plus any specific to
your business requires additional guidance for data stakeholders. Remember, the policy sets forth the
minimum expectations for the company.12 What Is Data Governance?
To get started in developing your data governance policy, a suggested data governance policy outline
may contain the following:
1. Purpose and scope statement (for example, to transform how the company utilizes data by
creating additional revenue streams and simultaneously reducing data risk)
2. The owner (for example, a Chief Data Officer)
3. Reviewers/contributors and titles (for example, Head of IT, COO, and data stewards)
4. Sign-off/approval (For example, CEO, CFO, and so on)
5. Data governance requirements
6. Roles and responsibilities for implementation
7. Feedback loops for improvements and/or additions
8. Measures of success
9. Compliance/audit expectations and frequency
10. Glossary of terms
Data governance policy example
The following is an example of an enterprise data governance policy:
Owner: Chief Data & Analytics Officer
Last Approval: 12/31/2023
Policy Leader: Head of Data Governance
Contributors:
• Head of Information Technology/CIO
• Head of Human Resources/CHRO
• Head of Marketing/CMO
• Head of Sales/CRO
• Product/Business Unit Leaders
• Product/Business Unit Data StewardsA brief overview of the data governance components 13
Purpose and scope
This data management policy applies to all data held or processed by the company, which may include
customer data, transactional data, financial information, regulatory and risk reporting, and any other
data related to the business of the company. This data may be first-party data, derived data, or data
acquired from another company (third-party data). The outcomes of this policy are the following:
• Reduce risk
• Unlock revenue opportunities
• Drive operational efficiencies
Introduction
The company is responsible for ensuring all data is accurate, complete, secure, and accessible only to
those who require access to fulfill their job responsibilities. This policy sets for the requirements for
the enterprise to deliver on the outcomes established above.
Data governance
Data governance establishes the requirements and standards for all corporate data deemed “in scope”
of this policy in the aforementioned policy and scoping section. The purpose of the data governance
capabilities established within this policy are to drive enhanced transparency and accountability for
our company’s data and to drive improved consistency, control, and oversight for how data is managed,
stored, and used going forward.
Roles and responsibilities
1. Enterprise Data Committee: An Enterprise Data Committee will be established, chaired by the
Chief Data & Analytics Officer, to provide an oversight and prioritization body to manage data
and analytics initiatives and issue remediation enterprise-wide. A Data Domain Executive will
be required to sit on this committee to ensure appropriate prioritization across all data domains.
2. The Chief Information Officer will partner with the Chief Data & Analytics Officer to ensure
technical requirements and systems are provided in support of the data and analytical needs
of the organization, both for the Office of the Chief Data & Analytics Officer, but also for all
functional data domains enterprise-wide.
3. A Data Domain Executive will be established for each functional area to ensure the appropriate
focus, funding, and resourcing is established and maintained to manage data in accordance
with both this policy and the needs of the business.
4. Data Stewards will be assigned by each Data Domain Executive to ensure the day-to-day
execution of data requirements is completed in accordance with policy and the needs of the
business. Data Stewards will also be required to work with the Office of the Chief Data &
Analytics Officer to ensure that transparency of progress and ongoing operational effectiveness
is maintained for leadership, regulators, and across domains.14 What Is Data Governance?
Requirements
This section provides the minimum expectations for compliance.
Data Governance
Each data domain will develop a plan to drive compliance with this policy to operationalize the
requirements within their data domain. The Data Domain Executive will ensure appropriate prioritization,
whereas the Data Stewards will execute the plan on behalf of the Data Domain Executive. Additionally,
Technical Data Stewards will support the delivery of all technical requirements to ensure compliance
with this policy and the broader needs of the business. The minimum requirements are the following:
1. Identify all data assets and systems
2. Identify all data and technical data stewards for each asset and system
3. Assign each asset and system to the appropriate data domain
4. Develop a plan to meet the requirements for each asset and system and maintain compliance
going forward
Data Cataloging
The purpose of data cataloging is to centrally manage and publish business and technical metadata
across the organization to enable accelerated discovery of the data available across the organization in
a clear, transparent manner. As data cataloging is implemented, the Chief Data & Analytics Office will
evaluate metadata to determine the best source of truth for a given data asset and identify opportunities
to reduce proliferation and redundancy across the company. This will further simplify our data
ecosystem over time and reduce the costs of duplicate data handling/management and storage. The
minimum requirements to be published in the Enterprise Data Catalog are the following:
1. Description of the data asset/system
2. Technical metadata
3. Description of schemas and tables
4. Identification of critical data elements (CDEs)
5. Business definitions for CDEs
6. Data classification for all data elements within the asset/system in accordance with the company
data classification policyA brief overview of the data governance components 15
Data Quality
The purpose of data quality is to ensure the data is fit for use. The following requirements have been
set forth with the aim to centrally develop data quality rules, provide profiling resources and tooling,
and monitor data hygiene to ensure the data can be trusted for analytical and business use and identify
issues requiring disclosure and/or remediation. The minimum requirements are the following:
1. Define the data quality rules for each CDE and enter this into the enterprise data quality tool
2. Enable CDEs for data quality monitoring
3. Provide data quality dashboards to transparently report on current quality levels
4. Identify data quality issues and create plans to address material data quality issues
Policy Management
• Feedback Loops: Feedback about the policy and/or questions about policy implementation
should be directed to the Policy Leader defined above.
• Measures of Success: A robust Enterprise data governance scorecard will be established for
each data domain and at the corporate level. Periodic reporting of the progress of complying
with this policy will be reported to the Office of the Chief Data & Analytics Officer and to the
Enterprise Data Committee. Further measures of success may be required.
• Compliance/Audit: Internal audits, external audits, and regulatory bodies may audit this policy
for compliance on a regular basis. All requests for audit should be disclosed to the Office of
the Chief Data & Analytics Officer so that requests can be co-ordinated and driven through
the Enterprise Data Committee.
• Frequency: This policy will be reviewed, updated, and re-approved at least annually.
Now that we’ve reviewed what makes up a great policy, let’s pivot into the key roles and responsibilities
for a data governance program.
Roles and responsibilities
Any data governance expert will tell you that people are the key to a successful data governance
program. People are responsible for caring for the data and ensuring its accuracy, that it is fit for use,
and how to improve it to make it better. This concept is called data stewardship. Data stewardship
requires collaboration to drive success. The executive identified for each data domain appoints a data
steward to drive day-to-day activities for the data domain.
The key responsibilities of data stewards include the following:
• Serve as the single point of leadership for their data domain
• Ensure the data domain executive is kept informed on key activ