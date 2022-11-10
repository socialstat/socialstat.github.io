Measuring corruption and its risk is utmost important to fight this detrimental phenomenon. Recent approaches in this field have focused on corruption prevention, rather than its repression. Among them, red flag indicators are very useful tools. In fact, being correlated to misconducts and malpractices, they allow us to identify, in advance, situations at risk of corruption. Red flags are often considered in public procurement, as the latest is a sector particularly vulnerable to corruption, due to the volume of the economic transactions and financial interests at stake, other than the process complexity and the close interaction between public officials and businesses. However, prior to organising a strong red flag indicator system, it is essential to depend on reliable data regarding the public procurement process.The Italian National Database of Public Contracts (BDNCP) is a huge open dataset collecting every single public contract managed by Italian institutions. It contains 53 million procedures over the period 2009-2021 with 2.4 trillion euros in contract total value. Still, information on contracts below the Italian threshold (which accounts for more than 90% of the total volume) is very limited and therefore not sufficient for constructing a set of reliable red flags. In this respect, we propose a modern data integration procedure aimed at augmenting the BDNCP through the exploitation of other data sources, such as the list of communications yearly published by each public administration on its website in xml format (pursuant to art. 1, paragraph 32, of law 190/2012). The annual communication contains basic information about all the public contracts managed by each contracting authority, such as, among others, participating companies, winner(s), contract starting and ending dates, and final sums paid. For most contracts, all the last pieces of information are missing in the BDNCP, as well as in any other national and international datasets currently in use by researchers and policy makers. The proposed data integration system implies a high number of in-between transformations to ensure its usability. Thus a paradigm shift from traditional ETL (extract, transform, load, i.e. integrate) to ELT (extract, load, transform) must take place because it is almost impossible to finish these operations before integration.This results in both higher data quality and availability. Advantages of this paradigm come from the fact that the extraction step is moved closer to the integration step, in such a way as to allow us to prevent common failures during transformations and incremental technical debt. This work is part of the activities carried out under the project CO.R.E (COrruption Risk indicator in Emergency),  funded under the EU Security Fund Police (ISF-P) call, which intends to develop and validate a statistical procedure for constructing a composite indicator (CI) for the risk of corruption in emergency over massive unstructured big web data sources in public procurement. To this aim, the above data integrating procedure is instrumental to i. develop appropriate elementary indicators to be entered in the corruption risk CI procedure and ii. assess its validity through sensitivity analysis. 