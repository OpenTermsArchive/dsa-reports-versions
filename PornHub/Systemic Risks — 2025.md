Report on the results of the risk

assessment for Pornhub.com pursuant

to Article 34 of the Digital Services Act



Aylo Freesites Limited – April 2025

Pornhub.com (“Pornhub”) is an online platform provided by Aylo Freesites Limited. The platform has

been designated as a very large online platform according to Article 33 of the Digital Services Act

(Regulation EU 2022/2065) by the European Commission on 20 December 2023. Pursuant to Article

34 of the Digital Services Act, Aylo has identified, analyzed and assessed systemic risks in the Union

resulting from, or influenced by, the design and functioning of Pornhub.com and its related systems,

including algorithmic systems, or from the use made of the service.



This report sets out the results of this risk assessment.



This report is authored by



Aylo Freesites Ltd,

Block 1,

195-197 Old Nicosia-Limassol Road,

Dali Industrial Zone,

Cyprus 2540



April 2025

Frustration due to

unrealistic

expectations



Slight – Marginal Remote Low - Medium



Overarching

factors

Ad Delivery Critical Improbable Medium



Recommender

Systems

Critical Improbable Medium



Since all risk levels are in the range of medium to low because of the extensive risk mitigation

measures Aylo has implemented, the residual risks do not require additional mitigation measures

according to Article 35 of the Digital Services Act.

Summary of most relevant factors

considered in the risk assessment for

Pornhub pursuant to Article 34 of the

Digital Services Act



Aylo Freesites Limited – April 2025

Table of contents



Dissemination of illegal content.................................................................................................8

Child sexual abuse material (CSAM) ....................................................................................8

Non-consensual content (NCC) – Acts, Recordings, Distribution, and Manipulation ............16

Doxing and harassment.....................................................................................................22

Copyright infringements....................................................................................................27

Terrorism..........................................................................................................................31

AI generated content representing illegal acts ....................................................................36

Fundamental rights...................................................................................................................37

Hate speech and fostering stereotypes regarding sexual preferences and behaviour............37

Sex trafficking...................................................................................................................41

Data minimization.............................................................................................................46

Civic Discourse, electoral process and public security ............................................................47

Politically provocative content and adverts ........................................................................47

Deep fakes .......................................................................................................................52

Over-blocking...................................................................................................................53

Gender based violence, public health, minors, physical and mental well-being ......................56

Negative effects in relation to minors.................................................................................56

Porn addiction ..................................................................................................................63

Negative effects on relationships.......................................................................................65

Pornography fostering abuse and violence .........................................................................67

Frustration due to unrealistic expectations ........................................................................71

Overarching factors..................................................................................................................72

Ad delivery........................................................................................................................72

Recommender systems ....................................................................................................74

- 10 -



• Submit a government-issued ID, which is authenticated by the provider.



• Conduct a liveness test to ensure the users likeness matches the government-issued ID and they

are one and the same person.



• The liveness test also ensures that the person is alive and real, not AI, not pre-recorded, not a still

image.



At time of signup, and again at the time of each upload, all uploaders are required to attest that they

have obtained and retained ID and consent to record and distribute content from all other performers

appearing in their content.



As part of Pornhub’s more extensive verification processes, for individual content creators these

requirements are validated at least once per additional performer:



• Uploaders may meet the ID and consent verification requirement for their co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our internal

moderators review the result of the ID and liveness, and the terms of the consent form.



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our internal moderators verifying the result of the ID validation,

that the face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by our internal moderators, verifying the face of the co-performer

matches the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performersmust be approved by a member of our internalmoderation team. All performers

appearing in uploaded content are checked by the moderators against approved co-performers,

to ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer. If there is any doubt, then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

- 11 -



for individual verified uploaders to submit ID and consent paperwork for all co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog

post.: https://www.pornhub.com/blog/2025-consent-and-id-requirement-updates.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, studio-produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually, they are not required to provide us with IDs

for all performers prior to content publication. This part of the verification process is managed by

the studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust and comprehensiveprocess deters andhelpsto mitigate therisksrelatingto potential

uploads of illegal material and to the potential commission of illegal acts on the platform.



Software tools are in place to detect known CSAM before publication



• PhotoDNA scansallimages and YouTubeCSAIMatch scans all videos againsthash-listsofknown

CSAM from the following organisations:



o The Internet Watch Foundation: Image Hash List - Image Hash List (iwf.org.uk)



o Thorn: Safer - How CSAM Detection Works | Safer by Thorn



o National Center for Missing and Exploited Children: Hash sharing - CyberTipline Data

(missingkids.org) and Take it Down - Take It Down (ncmec.org)



o Offlimits: Instant Image Identifier - Offlimits | Home



o Aylo’s own hash databases from Mediawise and Safeguard



• PhotoDNA uses perceptual hashing techniques to scan uploaded content for matches against

known CSAM hash-lists – PhotoDNA | Microsoft.

- 12 -



• Matches prevent the content from being published. This reduces the risk of CSAM from being

published on the platform.



Software tools are in place to assist in the detection of unknown CSAM before publication



• All images and videos are scanned using three similar tools to help detect underage material :

o Google Content Safety API: Developing and sharing tools to fight child sexual abuse

(protectingchildren.google) and in particular the testimonial from NCMEC



o Thorn’s Safer: How CSAM Detection Works | Safer by Thorn



o Aylo’s Age Estimation: We use a detection model to output an age score estimating the

performers age.



• Each piece of software scans faces within uploads to ascertain whether a performer appears to

be underage. Results of these scans are passed to human moderators to aid moderation of

content uploads before publication. Different tools are used as, whilst similar, they function in

different ways. This ensures a threefold check on all uploaded material. If tools believe a

performer is underage then human moderators are alerted and will further scrutinise the material

to aid in publication decisions. This drastically reduces the risk of CSAM being published on

Pornhub.



Human moderation



• All images and videos are reviewed by at least one human moderator before being published on

Pornhub. Human moderators check that the IDs provided by uploaders and performers match

those within the material. If there are any concerns, then the moderator will reach out to the

uploader to supply more information and documentation. Human moderators use the results

from all tools to assist them in assessing the content and only publish material once they are

confident that the material meets all of our policies and guidelines. Requiring moderation of all

images and videos before publication, severely limits the likelihood of CSAM appearing on the

platform.



Downloads are not permitted



• Downloads of content are not permitted on Pornhub and no download functionality is made

available. This reduces the risk of content being downloaded and re-distributed on other

platforms after takedown, reducing the harms associated with re-victimisation.



Fingerprinting illegal material



• All potential CSAM that has been flagged by moderators, either during the upload process, or

subsequently removed, is fingerprinted (hashed) using two pieces of software:



o Mediawise by Vobile – This is based on third-party MD5 flat file hashing.

o Safeguard by Aylo – This is based on first-party perceptual hashing which can detect

manipulated media which may appear different to the original upload. For example if

material is edited in length, has changed in colouring or added watermarks, the material

is still detected as the same media and prevented from being re-uploaded.

- 13 -



• These fingerprints are scanned before publication. This reduces the risk of previously identified

CSAM from being re-uploaded to the platform.



Banned Words List



• The platform utilises a database of banned words and phrases, which are prevented from being

entered into all user-input fields, including titles, descriptions, tags, playlists, and searches. The

database contains words and terms from multiple sources, including NGOs, law enforcement,

and the platform’s own. See for example the IWF Keyword List – Keywords List (iwf.org.uk).

Preventing the use of terms associated with CSAM reduces the risk of CSAM publication.



Deterrence messaging



• Searches for words and phrases associated with CSAMand within theplatform’s database, result

in a CSAM deterrence message being shown and no results surfaced. A global deterrence

message is provided by The Lucy Faithfull Foundation in the United Kingdom, and many

jurisdiction specific messages are displayed, as provided by local NGOs who specialise in child

protection and potential offender behaviour. Deterrence messages direct those who seek for

CSAM terms within the platforms database, to seek help from the relevant NGO partner.

Deterrence messages also starkly inform the user that what they are searching is illegal, children

will have been harmed in its creation, and it cannot be found on the platform. Deterrence

messagingnot onlyprevents users fromsearching for CSAMmaterial, but also informs, educates,

and provides help to those who are searching. Reducing the risk of users wishing to consume

such material in the first place. The successful effects of deterrence messaging are explored in

this paper by the Lucy Faithfull Foundation, which also makes express reference to the use of this

safeguard on Pornhub.



•



Chatbot



• In partnership with the Internet Watch Foundation and the Lucy Faithfull Foundation, we

launched a chatbot on Pornhub in the UK as their exclusive pilot partner in March 2022. The

chatbot seeks to engage with adult pornography users attempting to search for sexual imagery of

children. The results from the pilot were evaluated by the University of Tasmania and showed

success.



Contextual Text Moderation



• Users can comment underneath videos presented on the platform. These comments are

moderated using third-party software from Spectrum Labs AI. The software scans comments in a

contextual manner, for multiple bad behaviours including the discussion of CSAM. Any volitive

- 14 -



comments are automatically removed from the site. This further reduces the likelihood of CSAM

material, even in written form, from appearing on the platform.



De-listing of URLs from search results



• If CSAM material is subsequently removed from the platform then the URL is provided to search

engines to de-list the link and prevent the material (whilst already removed) from appearing in

search results of search engines.



Trusted Flagger Program



• Pornhub operates a trusted flagger program comprising 66 members who specialise in the

removal of CSAM and Non-consensual content (NCC) from the internet. Most are NGOs who

receive communications directly from members of the public to report content of themselves or

others, that they believe is CSAM or NCC. Some law enforcement entities and government

agencies are also part of the trusted flagger program.



• Trusted flaggers can report content for removal directly to the platformand all content reported

in this manner is immediately and automatically de-published from the platform, then

subsequently reviewed. The program ensures that NGOs can very quickly remove content,

therefore reducing the risk of viewing by users of the platform, and limiting the harm to victims.



Content Removal Request



• A content removal request form (CRR) is linked at the bottom of every page on the platform.

Content reported in this manner is immediately and automatically removed, once the reporter

has confirmed their email address. This reduces the risk of viewing material and limits harm to

victims.



• The platform also offers an anonymous CSAM reporting form where an email address is not

required. Material reported in this manner is reviewed within just a few hours and de-published if

it is found to violate our CSAM policy.



Content Flagging



• The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours and

de-published ifit is found to violate our CSAMpolicy. This reducesthe risk ofviewing materialand

limits harm to victims.



User Profiles and Comments



• Profile pictures are treated as uploaded images, per our moderation process and are therefore

moderated via tools and humans to ensure they do not breach our Terms of Service.



• Usernames are scanned using our Banned Words List (see below) to reduce the likelihood of

terms associated with minors or CSAM being used.



• Whilst we permit anonymoususer profiles, userscannotpost images or videosprior to an identity

verification as referenced above. Therefore, our mitigation measures severely limit the likelihood

that users share CSAM.

- 15 -



• Our Banned Words List and Contextual Text Moderation also act on comments posted by all

registered users.



Messaging



• The platform does not allow unregistered users to message anyone else on the platform.



• The platform does not allow registered users to message other users, only content creators .



• The platform does not allow images, videos or attachments to be sent through the messaging

system.



• All users can be reported using the in-built functionality of the site.



• These policies and the raft of mitigation measures for all content severely limit the likelihood that

CSAM or CSAM URLs are communicated via messages on the platform.

- 18 -



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by our internal moderators, verifying the face of the co-performer

matches the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performers must be approved by a member of our moderation team. All performers

appearing in uploaded content are checked by the moderators against approved co-performers,

to ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer . If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for all co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, studio-produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs

for all performers prior to content publication. This part of the verification process is managed by

the studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation

- 19 -



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



Withdrawal of consent



• Performers who previously consented to the distribution of content on the platform can withdraw

their consent at any time. This will result in the content being removed from the platform and can

be reported via the CRR or by contacting our support team.



Software tools are in place to detect known non-consensual intimate images (NCII) before

publication



• PhotoDNA scans all images, and YouTube CSAI Match scans all videos, against hash-lists of

known NCII from the following organisation:



o STOPNCII.org (part of the Revenge Porn Helpline)



• Matches prevent the content from being published. This reduces the risk of NCII from being

published on the platform.



Human moderation



• All images and videos are reviewed by at least one human moderator before being published on

the platform. Human moderatorscheck that theIDs providedby uploadersand performersmatch

those within the material. If there are any concerns, then the moderator will reach out to the

uploader to supply more information and documentation. Human moderators use the results

from all tools to assist them in assessing the content and only publish material once they are

confident that the material meets all of our policies and guidelines. Requiring moderation of all

images and videos before publication, severely limits the likelihood of NCC appearing on the

platform.



Downloads are not permitted



• Downloads of content are not permitted on Pornhub, and no download functionality is made

available. This reduces the risk of content being downloaded and re-distributed on other

platforms even after takedown from Pornhub, reducing the harms associated with re-

victimisation.



Fingerprinting illegal material



• All NCC that has been flagged by moderators, either during the upload process, or subsequently

removed, is fingerprinted (hashed) using two pieces of software:



o Mediawise by Vobile – This is based on third-party MD5 flat file hashing.

o Safeguard by Aylo – This is based on first-party perceptual hashing which can detect

manipulated media which may appear different to the original upload. For example if

- 20 -



material is edited in length, has been changed in colouring, or has added watermarks, the

material is still detected as the same media and prevented from being re-uploaded.



• These fingerprints are scanned before publication. This reduces the risk of previously identified

NCC from being re-uploaded to the platform.



Banned Words List



• The platform utilises a database of banned words and phrases, which are prevented from being

entered into all user-input fields, including titles, descriptions, tags, playlists, and searches. The

database contains words and terms from multiple sources, including NGOs, law enforcement,

and the platformsown. Preventing theuseofterms associated withall categories ofNCC reduces

the risk of NCC publication.



Deterrence messaging



• Searches for words and phrases associated with NCC and within the platform’s database, result

in an NCC deterrence message being shown and no results surfaced. A global deterrence

message is provided by the Cyber Civil Rights Initiative in the United States of America, and many

jurisdiction specific messages are displayed, as provided by local NGOs who specialise in NCC

removal and victim support. Deterrence messages inform the user that what they are searching

for is illegal and it cannot be found on the platform. Users are directed to NGOs who can help

them if they are the victim of such material, and how to remove it if it appears on the platform or

on other sites, via NGO resources. Deterrence messaging not only prevents users from searching

for NCC material, but also informs, educates, and provides help to those who are searching.

Reducing the risk of users wishing to consume such material in the first place.



Contextual Text Moderation



• Users can comment underneath videos presented on the platform. These comments are

moderated using third-party software from Spectrum Labs AI. The software scans comments in a

contextual manner, for multiple bad behaviours including the discussion of NCC. Any volitive

comments are automatically removed from the site. This further reduces the likelihood of NCC

material, even in written form, from appearing on the platform.



De-listing of URLs from search results



• If NCC material is subsequently removed from the platform then the URL is provided to search

engines to de-list the link and prevent the material (whilst already removed) from appearing in

search results of search engines.



Trusted Flagger Program



• Pornhub operates a trusted flagger program comprising 66 members who specialise in the

removal of CSAM and NCII from the internet. Most are NGOs who receive communications

directly from members of the public to report content of themselves or others, that they believe

is CSAM or NCII. Some law enforcement entities and government agencies are also part of the

trusted flagger program.

- 21 -



• Trusted flaggers can report content for removal directly to the platformand all content reported

in this manner is immediately and automatically de-published from the platform, then

subsequently reviewed. The program ensures that NGOs can very quickly remove content,

therefore reducing the risk of viewing by users of the platform, and limiting the harm to victims.



•



Content Removal Request



• A content removal request form (CRR) is linked at the bottom of every page on the platform. All

visitors to the platform can use the CRR to report NCC material by providing the URL of the

content, the reason why it should be removed, and an email address so that the platform can

communicate with the reporter, ask for more detail ifrequired, and confirmour decision. Content

reported in this manner is immediately and automatically removed, once the reporter has

confirmed their email address. This reduces the risk of viewing material and limits harm to

victims.



Content Flagging



• The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours and

de-published if it is found to violate our NCC policy. This reduces the risk of viewing material and

limits harm to victims.



Image-based Sexual Abuse Principles



• After the White House issued a Call to Action to Combat Image-Based Sexual Abuse for tech and

civil society on 23 May 2024, the Center for Democracy and Technology (CDT), the Cyber Civil

Rights Initiative (CCRI), and the National Network to End Domestic Violence (NNEDV) invited civil

society organizations and tech industry leaders to a multistakeholder working group (“Working

Group”) focused on combating Image-Based Sexual Abuse.



• Aylo participated in this working group, which worked to create a set of principles, which were

published in September 2024\. We are proud of our continued work to prevent non-consensual

content and hope that more organisations will sign-up to these voluntary principles.

- 23 -



https://www.pornhub.com/blog/increased-security-for-your-pornhub-account,

https://www.pornhub.com/blog/tips-on-how-to-manage-account-security-and-safety

and https://www.pornhub.com/blog/beware-of-phishing-scams-targeting-models



o Monthly newsletters are circulated when new security features become available on the

platform



o Campaigns with 3rd party performer advocacy groups are in the works to share tips and

knowledge on how performers can protect their address and other PII when filming

content in their home – Cupcake Girls and Pornhub Announce New Partnership



o Pornhub 101 series published for both users and models explain compliance and

community elements of the platform



• We are working with third party advocacy groups via our partnerships to create assets to help our

community better understand these as well.



Identity and consent

There are two types of uploaders on Pornhub: individual content creators, often referred to as

“Models”, and content partners, or third-party professional content studios.



As part of their registration, content partners are required to provide a company name,

company/studio content website, and physical address or URL indicating the coordinates of their

custodian of 2257 records (pursuant to record-keeping requirements for age and identity verification

under 18 U.S. Code § 2257, which requires creating and maintaining individually identifiable records

pertaining to every performer portrayed in a visual depiction that comprises adult content).



Every new uploader is required to undergo identity verification with a third-party identity verification

provider, which requires them to:



• Submit a government issued ID, which is authenticated by the provider.



• Conduct a liveness test to ensure the users likeness matches the government issued ID and they

are one and the same person.



• The liveness test also ensures that the person is alive and real, not AI, not pre-recorded, not a still

image.



At time of signup, and again at the time of each upload, all uploaders are required to attest that they

have obtained and retained ID and consent to record and distribute content from all other performers

appearing in their content.



As part of Pornhub’s more extensive verification processes, for individual content creators, these

requirements are validated at least once per additional performer:



• Uploaders may meet the ID and consent verification requirement for their Co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our

moderators review the result of the ID and liveness, and the terms of the consent form.

- 24 -



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our moderators verifying the result of the ID validation, that the

face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by internal moderators, verifying the face of the co-performer matches

the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performers must be approved by a member of the moderation team. All performers

appearing in uploaded content are checked by moderators against approved co-performers, to

ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer . If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, Studio produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content.. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs for

all performers prior to content publication. This part of the verification process is managed by the

studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:

- 25 -



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



User profiles



• The information displayed on user profiles is limited and set by the user themselves.



• Two-factor authentication is availableto all contentcreatorson theplatformto limit thelikelihood

of unauthorised access.



• Usernames cannot be edited by a user. Content creators can change their username and stage

name once per month without contacting a support agent.



• A user harassing a content creator is mitigated by the content creator’s ability to report the user,

who would be actioned by the support team.



• Content creators can also contact our support team directly if a pattern of bad behaviour occurs.



Fake User profiles



• Noted in the messaging section, user to user messaging is not possible on the platform, therefore

limiting the risk of users being harassed or contacted by other users.



Contextual Text Moderation



• Users can comment underneath videos presented on the platform. These comments are

moderated using third-party software from Spectrum Labs AI. The software scans comments in a

contextual manner, for multiple bad behaviours including the discussion of PII. Any volitive

comments are automatically removed from the site. This reduces the likelihood of

PII/doxing/harassment appearing on the platform.



Content Flagging



• The platform offers a way for logged-in users to flag all images, videos, comments, and users.

Content flagged in this manner will be reviewed by a moderator within just a few hours and de-

published if it is found to contain PII or doxing/harassment. Performers can flag users for doxing

and threats to the Model Support team. These are reported to the Trust \& Safety team to

determine if there is an imminent threat, and they will take who will take the appropriate action.

In most cases, the user is banned for violating our Terms of Service. This reduces the risk of

viewing material and limits harm to victims.



Messaging

- 26 -



• The platform does not allow unregistered users to message anyone else on the platform.



• The platform does not allow registered users to message other users, only content creators .



• The platform does not allow images, videos or attachments to be sent through the messaging

system.



• All users can be reported using the in-built functionality of the site.

- 28 -



• The liveness test also ensures that the person is alive and real, not AI, not pre-recorded, not a still

image.



At time of signup, and again at the time of each upload, all uploaders are required to attest that they

have obtained and retained ID and consent to record and distribute content from all other performers

appearing in their content.

As part of Pornhub’s more extensive verification processes, for individual content creators, these

requirements are validated at least once per additional performer:



• Uploaders may meet the ID and consent verification requirement for their Co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our

moderators review the result of the ID and liveness, and the terms of the consent form.



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our moderators verifying the result of the ID validation, that the

face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by internal moderators, verifying the face of the co-performer matches

the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performers must be approved by a member of the moderation team. All performers

appearing in uploaded content are checked by moderators against approved co-performers, to

ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer . If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).

- 29 -



• As it relates to content partners, Studio produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content.. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs for

all performers prior to content publication. This part of the verification process is managed by the

studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



Software tools are in place to detect known copyright material before publication



• There are two repositories of Vobile hashes:



o Hashes of content which violates our terms of service



o Copyright content hashes.



• Exclusive model content is automatically fingerprinted by Vobile in the latter repository. If that

content is uploaded by a different model in the future, the content will automatically be set to

infringing copyright status.



Human moderation



• All images and videos are reviewed by at least one human moderator before being published on

the platform. Human moderatorscheck that theIDs providedby uploadersand performersmatch

those within the material. If there are any concerns, then the moderator will reach out to the

uploader to supply more information and documentation. Human moderators use the results

from all tools to assist them in assessing the content and only publish material once they are

confident that the material meets all of our policies and guidelines. Requiring moderation of all

images and videos before publication, severely limits the likelihood of copyright material

appearing on the platform.



Downloads are not permitted

- 30 -



• Downloads of content are not permitted on the platform. This reduces the risk of content being

downloaded and re-distributed on other platforms even after having been taken down on

Pornhub.



Fingerprinting illegal material



• All copyright material(producesby exclusivemodels)that has been flaggedby moderators, either

during the upload process, or subsequently removed, is fingerprinted (hashed) using two pieces

of software:



o Mediawise by Vobile – This is based on third-party MD5 flat file hashing.



o Safeguard by Aylo – This is based on first-party perceptual hashing which can detect

manipulated media which may appear different to the original upload. For example if

material is edited in length, has changed in colouring, or added watermarks, the material

is still detected as the same media and prevented from being re-uploaded .



• These fingerprints are scanned before publication. This reduces the risk of previously identified

copyright material from being re-uploaded to the platform.



Tailored Reporting Forms



• Pornhub has DSA compliant content removal forms to report copyright infringements (alongside

any other form of illegal content). Additionally, we prevent and enforce against copyright

infringements globally with tailored processed and forms that take special requirements of non-

EU jurisdictions into account. Pornhub also has a dedicated page on DMCA removals linked at

the bottom of every page on the platform. Rights holders can use the DMCA form to report

copyright material by providing the URL of the content, a description of the work being infringed,

and full contact details. Content reported in this manner is reviewed by the DMCA team and

investigated for removal. This reduces the risk of copyright material and limits harm to victims

globally.

- 32 -



At time of signup, and again at the time of each upload, all uploaders are required to attest that they

have obtained and retained ID and consent to record and distribute content from all other performers

appearing in their content.



As part of Pornhub’s more extensive verification processes, for individual content creators, these

requirements are validated at least once per additional performer:



• Uploaders may meet the ID and consent verification requirement for their Co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our

moderators review the result of the ID and liveness, and the terms of the consent form.



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our moderators verifying the result of the ID validation, that the

face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by internal moderators, verifying the face of the co-performer matches

the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performers must be approved by a member of the moderation team. All performers

appearing in uploaded content are checked by moderators against approved co-performers, to

ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer . If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, Studio produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

- 33 -



maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content.. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs for

all performers prior to content publication. This part of the verification process is managed by the

studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



Membership of Tech Against Terrorism



• PH is a member of Tech Against Terrorism’s mentorship program – Tech Against Terrorism |

Disrupting Terrorist Activity Online which mentors platforms in preventing the dissemination of

terrorist material, giving access to threat intelligence, OSINT briefings, and a knowledge sharing

platform.



Terrorist Content Online Regulation compliance



• We comply with the Terrorist Content Online Regulation in the EU, requiring immediate takedown

of any material reported by the relevant authorities, as noted in our Terms of Service. “For any

removal orders pursuant to Regulation (EU) 2021/784 (the “Terrorist Content Online

Regulation” or “TCO”), designated competent EU authorities can complete our removal form.

After submission of this form, you will receive further instructions by e-mail, which you may

respond to with a removal order. For such removal orders, please use the template provided

in Annex I of the TCO and conduct all communication in either English or Greek.”



User Profiles



• Profile pictures are treated as uploaded images, per our moderation process and are therefore

moderated via tools and humans to ensure they do not breach our Terms of Service.



• Usernames are scanned using our Banned Words List (see below) to reduce the likelihood of

hateful terms being used.

- 34 -



• Usernames cannot be edited by a user. Content creators can change their username and stage

name once per month without contacting a support agent.



• Whilst we permit anonymous user profiles, our mitigation measures severely limit the likelihood

that users share terrorism material.



Human moderation



• All images and videos are reviewed by at least one human moderator before being published on

the platform. Human moderatorscheck that theIDs providedby uploadersand performersmatch

those within the material. If there are any concerns, then the moderator will reach out to the

uploader to supply more information and documentation. Human moderators use the results

from all tools to assist them in assessing the content and only publish material once they are

confident that the material meets all of our policies and guidelines. Requiring moderation of all

images and videos before publication, severely limits the likelihood of terrorist content appearing

on the platform.



Downloads are not permitted



• Downloads of content are not permitted on the platform. This reduces the risk of content being

downloaded and re-distributed on other platforms even after takedown from Pornhub, reducing

the harms associated with re-victimisation.



Fingerprinting illegal material



• All terrorist material that has been flagged by moderators, either during the upload process, or

subsequently removed, is fingerprinted (hashed) using two pieces of software:



o Mediawise by Vobile – This is based on third-party MD5 flat file hashing.



o Safeguard by Aylo – This is based on first-party perceptual hashing which can detect

manipulated media which may appear different to the original upload. For example if

material is edited in length, has been changed in colouring, or has added watermarks, the

material is still detected as the same media and prevented from being re-uploaded.



• These fingerprints are scanned before publication. This reduces the risk of previously identified

terrorist content from being re-uploaded to the platform.



Banned Words List



• The platform utilises a database of banned words and phrases, which are prevented from being

entered into all user-input fields, including titles, descriptions, tags, playlists, and searches. The

database contains words and terms from multiple sources, including NGOs, law enforcement,

and the platforms own. Preventing the use of terms associated with terrorism reduces the risk of

terrorist material publication.



De-listing of URLs from search results



• If terrorist material is subsequently removed from the platform then the URL is provided to search

engines to de-list the link and prevent the material (whilst already removed) from appearing in

search results of search engines.

- 35 -



Content Removal Request



• A content removal request form (CRR) is linked at the bottom of every page on the platform.

Content reported in this manner is immediately and automatically removed, once the reporter

has confirmed their email address. This reduces the risk of viewing material and limits harm to

victims.



Content Flagging

The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours and

de-published if it is found to violate our terms of service. This reduces the risk of terrorist material

from being viewed.



Contextual Text Moderation



• Users can comment underneath content presented on the platform, including videos and blog

posts. These comments are moderated using third-party software from Active Fence. The

software scans comments in a contextual manner, for multiple bad behaviours including the

discussion of violence. Any violative comments are reviewed and removed from the site.



Messaging



• The platform does not allow unregistered users to message anyone else on the platform.



• The platform does not allow registered users to message other users, only content creators.



• The platform does not allow images, videos or attachments to be sent through the messaging

system.



• All users can be reported using the in-built functionality of the site.



• These measures limit the likelihood that terrorist material can be shared on our platform.

- 38 -



• We define hate speech as any communication or material that promotes, calls for, supports, or

advocates for the delegitimization, dehumanization, discrimination, segregation, detestation, or

vilification of a person or group of persons by reason of the fact that they are identifiable on the

basis of protected characteristics. At its most extreme, hate speech calls for, threatens, or

promotes violence against people that are identifiable on the basis of protected characteristics.

Both our Terms of Service, and our policy on hate speech prohibit any material featuring hate

speech.



User Profiles



• Usernames are scanned using our Banned Words List (see below) to reduce the likelihood of

hateful terms being used.



• Usernames cannot be edited by a user. Content creators can change their username and stage

name once per month without contacting a support agent.



• Profile pictures are treated as uploaded images, per our moderation processes and are therefore

moderated via tools and humans to ensure they do not breach our Terms of Service.



• Whilst we permit anonymous user profiles, our mitigation measures severely limit the likelihood

that users share hateful material.



Banned Words List



• The platform utilises a database of banned words and phrases, which are prevented from being

entered into any user-input fields, including titles, descriptions, tags, playlists, and searches. The

database contains words and terms from multiple sources, including NGOs, Law Enforcement,

and the platforms own.



Contextual Text Moderation



• Users can comment underneath videos presented on the platform. These comments are

moderated using third-party software from Spectrum Labs AI. The software scans comments in a

contextual manner, for multiple bad behaviours including hate speech. Any violative comments

are automatically removed fromthe platform. This further reducesthelikelihood ofdiscriminating

material, even in written form, from appearing on the platform.



Human moderation



• All images and videos are reviewed by at least one human moderator before being published on

the platform. Human moderators use the results from all tools to assist them in assessing the

content and only publish material once they are confident that the material meets all of our

policies and guidelines. Requiring moderation of all images and videos before publication,

severely limits the likelihood of discriminatory content appearing on the platform



Content Removal Request



• A content removal request form (CRR) is linked at the bottom of every page on the platform. All

visitors to the platformcan use theCRR to reportmaterialby providing the URL ofthe content, the

reason why it should be removed, and an email address so that the platform can communicate

- 39 -



with the reporter, ask for more detail if required, and confirm our decision. Content reported in

this manner is immediately and automatically removed, once the reporter has confirmed their

email address. This reduces the risk of viewing material and limits harm to victims.



Content Flagging



• The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours and

de-published if it is found to violate our Terms of Service. This reduces the risk of viewing material

and limits harm to victims.



Law enforcement portal



• We host a law enforcement portal so that law enforcement is able to quickly request information

from the platform to assist with legal cases.



Messaging



• The platform does not allow unregistered users to message anyone else on the platform.



• The platform does not allow registered users to message other users, only content creators .



• The platform does not allow images, videos or attachments to be sent through the messaging

system.



• All users can be reported using the in-built functionality of the site.



• These policies and mitigation measures lower the risk of messaging being used to facilitate the

spread of hate.



Freedom of Sexual Expression



• When acted out by consenting adults in safe environments and adhering to our Terms of Service,

desires, fetishes and fantasies are welcomed and supported on our platform. Pornography does

not always represent sexual interactions and behaviours typical of everyday life, and can depict

diverse fantasies and role-play by consenting amateurs and professionals.



Strengthening a resilient community



• Donating to BIPOC Adult Industry Collective for Black History Month: We donated to the BIPOC

Adult Industry Collective, an organization offering resources, education, and support services to

help fight racism in the adult entertainment industry. The organization pursues this mission

through various programs and activities designed to help community members reach their goals

and fulfil their potential.

• Celebrating Excellence Throughout Black History Month: Our team is committed to fighting the

stigma associated with sex work year-round. This Black History Month, we’re contributing to this

goal by humanizing Performers and creating links of recognition and understanding with those

outside the adult entertainment industry through a Black Model Spotlight Series!

• Demystifying LGBTQ+ Slang in the Adult Industry: There’s a lot of information online about the gay

community, however some of it is rather incomplete, and sometimes downright offensive. We

hope to clear away some of the confusion and offer you a clear and detailed breakdown of some

- 40 -



of the terms commonly used by lesbian, gay, bisexual, transgender, queer, and pansexual

groups.

- 42 -



Resources for performers



• Guidelines are given to performers to help them understand how to protect their identity. This

includes:



o Educational blog posts with best practices for safety and security measures are

published frequently, including:

https://www.pornhub.com/blog/increased-security-for-your-pornhub-account,

https://www.pornhub.com/blog/tips-on-how-to-manage-account-security-and-safety

and https://www.pornhub.com/blog/beware-of-phishing-scams-targeting-models



o Monthly newsletters are circulated when new security features become available on the

platform



o Campaigns with 3rd party performer advocacy groups are in the works to share tips and

knowledge on how performers can protect their address and other PII when filming

content in their home – Cupcake Girls and Pornhub Announce New Partnership

o Pornhub 101 series published for both users and models explain compliance and

community elements of the platform



• We are working with third party advocacy groups via our partnerships to create assets to help our

community better understand these as well.



Identity and consent



There are two types of uploaders on Pornhub: individual content creators, often referred to as

“Models”, and content partners, or third-party professional content studios.



As part of their registration, content partners are required to provide a company name,

company/studio content website, and physical address or URL indicating the coordinates of their

custodian of 2257 records (pursuant to record-keeping requirements for age and identity verification

under 18 U.S. Code § 2257, which requires creating and maintaining individually identifiable records

pertaining to every performer portrayed in a visual depiction that comprises adult content).



Every new uploader is required to undergo identity verification with a third-party identity verification

provider, which requires them to:



• Submit a government-issued ID, which is authenticated by the provider.



• Conduct a liveness test to ensure the users likeness matches the government-issued ID and they

are one and the same person.



• The liveness test also ensures that the person is alive and real, not AI, not pre-recorded, not a still

image.



At time of signup, and again at the time of each upload, all uploaders are required to attest that they

have obtained and retained ID and consent to record and distribute content from all other performers

appearing in their content.



As part of Pornhub’s more extensive verification processes, for individual content creators, these

requirements are validated at least once per additional performer:

- 43 -



• Uploaders may meet the ID and consent verification requirement for their co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our internal

moderators review the result of the ID and liveness, and the terms of the consent form.



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our internal moderators verifying the result of the ID validation,

that the face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by our internal moderators, verifying the face of the co-performer

matches the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performersmust be approved by a member of our internalmoderation team. All performers

appearing in uploaded content are checked by the moderators against approved co-performers,

to ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer. If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, Studio produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content.. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs for

all performers prior to content publication. This part of the verification process is managed by the

studios, and they are required to provide all documentation on demand:

- 44 -



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



• .



Withdrawal of consent



• Performers who previously consented to the distribution of content on the platform can withdraw

their consent at any time. This will result in the content being removed from the platform and be

reported via the CRR.



Beneficiary controls



• Only the ID verified, main account holder can receive payments from their account on the

platform. When an account is held by a couple, the beneficiary can be either individual.



Banned Words List



• The platform utilises a database of banned words and phrases, which are prevented from being

entered into all user-input fields, including titles, descriptions, tags, playlists, and searches. The

database contains words and terms from multiple sources, including NGOs, law enforcement,

and the platforms own.



Human moderation



• All uploaded images and videos are reviewed by at least one human moderator before being

published on the platform. Human moderators check that the IDs provided by uploaders and

performers match those within the material. If there are any concerns, then the moderator will

reach out to the uploader to supply more information and documentation. Human moderators

use the results from all tools to assist them in assessing the content and only publish material

once they are confident that the material does not violate our policies and guidelines. Requiring

moderation of all images and videos before publication, limits the likelihood of content featuring

victims of trafficking occurring.



Content Removal Request

- 45 -



• A content removal request form (CRR) is linked at the bottom of every page on the platform. All

visitors to the platformcan use theCRR to reportmaterialby providing the URL ofthe content, the

reason why it should be removed, and an email address so that the platform can communicate

with the reporter, ask for more detail if required, and confirm our decision. Content reported in

this manner is immediately and automatically removed, once the reporter has confirmed their

email address. This reduces the risk of viewing material and limits harm to victims.



Content Flagging



• The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours and

de-published if it is found to violate our Terms of Service. This reduces the risk of viewing material

and limits harm to victims.



Law enforcement portal



• We host a law enforcement portal so that law enforcement is able to quickly request information

from the platform to assist with legal cases.



Messaging



• The platform does not allow unregistered users to message anyone else on the platform.



• The platform does not allow registered users to message other users, only content creators .



• The platform does not allow images, videos or attachments to be sent through the messaging

system.



• All users can be reported using the in-built functionality of the site.



• All messaging is un-encrypted.



Partnership with the Cupcake Girls



• The CupcakeGirls arean organization that provides advocacy and referral services to consensual

sex workers, as well as prevention and aftercare services to those affected by sex trafficking. By

sharing resources – ranging from collective collaborations to data insights – and by engaging with

sex workers, thegoalis to support consensualsex workersand foster an environment wheretheir

safety and success is prioritized.



• We partnered with the Cupcake Girls in September 2023 to support consensual sex workers and

foster an environment where their safety and success is prioritised.



• In March 2025, Aylo announced a first-of-its-kind trafficking prevention safety video series for

adult performers.

- 48 -



• Conduct a liveness test to ensure the users likeness matches the government-issued ID and they

are one and the same person.



• The liveness test also ensures that the person is alive and real, not AI, not pre-recorded, not a still

image.



At time of signup, and again at the time of each upload, all uploaders are required to attest that they

have obtained and retained ID and consent to record and distribute content from all other performers

appearing in their content.

As part of Pornhub’s more extensive verification processes, for individual content creators, these

requirements are validated at least once per additional performer:



• Uploaders may meet the ID and consent verification requirement for their co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our internal

moderators review the result of the ID and liveness, and the terms of the consent form.



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our internal moderators verifying the result of the ID validation,

that the face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by internal moderators, verifying the face of the co-performer matches

the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performers must be approved by a member of the moderation team. All performers

appearing in uploaded content are checked by moderators against approved co-performers, to

ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer. If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.

- 49 -



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, Studio produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content.. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs

for all performers prior to content publication. This part of the verification process is managed by

the studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help, including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



User Profiles



• User profiles on the platform show a limited amount of information which can be set by the user.

The nature of our platform is such that it is unlikely to be targeted by those who wish to engage in

foreign interference by targeting users via their profiles.



• Profile pictures are treated as uploaded images, per our moderation process and are therefore

moderated via tools and humans to ensure they do not breach our Terms of Service.



• Anonymous users cannot post images and videos.



• Whilst we permit anonymous user profiles, our mitigation measures severely limit the likelihood

that users share foreign interference information.



Fake User profiles



• Noted in the messaging section, user to user messaging is not possible on the platform, therefore

limiting the risk of users being exploited by other users.



• Authoritative and high-profile sources are highly unlikely to create profiles on the platform due to

the type of platform, nor would users expect this to the case, therefore limiting the likelihood that

users would take anyone impersonating such a source, seriously.

- 50 -



• A user messaging a content creator is mitigated by the content creator’s ability to report the user,

who would be actioned by the support team.



• Content creators can also contact our support team directly if a pattern of bad behaviour occurs.



Contextual Text Moderation



• Users can comment underneath content presented on the platform, including videos and blog

posts. These comments are moderated using third-party software from Active Fence. The

software scans comments in a contextual manner, for multiple bad behaviours, including spam

and associated URLs, hyperlinking in this regard would fall into. Any violative comments are

reviewed and removed from the platform.



Human moderation



• All uploaded images and videos are reviewed by at least one human moderator before being

published on the platform. Human moderators check that the IDs provided by uploaders and

performers match those within the material. If there are any concerns, then the moderator will

reach out to the uploader to supply more information and documentation. Human moderators

use the results from all tools to assist them in assessing the content and only publish material

once they are confident that the material does not violate our policies and guidelines. Requiring

moderation of all images and videos before publication, severely limits the likelihood of any risk

to civic discourse, electoral process and public security.



Downloads are not permitted



• Downloads of content are not permitted on the platform, and no download functionality is made

available. This reduces the risk of content being downloaded and re-distributed on other

platforms.



Fingerprinting illegal material



• All potential politically proactive content that has been flagged by moderators, either during the

upload process, or subsequently removed, is fingerprinted (hashed)using twopiecesofsoftware:



o Mediawise by Vobile – This is based on third-party MD5 flat file hashing.



o Safeguard by Aylo – This is based on first-party perceptual hashing which can detect

manipulated media which may appear different to the original upload. For example if

material is edited in length, has changed in colouring, or added watermarks, the material

is still detected as the same media and prevented from being re-uploaded.



• These fingerprints are scanned before publication. This reduces the risk of previously identified

politically provocative content from being re-uploaded to the platform.



De-listing of URLs from search results



• If politically provocative material is subsequently removed from the platform then the URL is

provided to search engines to de-list the link and prevent the material (whilst already removed)

from appearing in search results of search engines.

- 51 -



Content Removal Request



• A content removal request form (CRR) is linked at the bottom of every page on the platform.

Content reported in this manner is immediately and automatically removed, once the reporter

has confirmed their email address. This reduces the risk of viewing material and limits harm to

victims.



Content Flagging



• The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours

and de-published if it is found to violate our policies. This reduces the risk of viewing material

and limits harm to victims.



Law enforcement portal



• We host a law enforcement portal so that law enforcement is able to quickly request information

from the platform to assist with legal cases.



Messaging



• The platform does not allow unregistered users to message anyone else on the platform.



• The platform does not allow registered users to message other users, only content creators.



• The platform does not allow images, videos or attachments to be sent through the messaging

system.



• All users can be reported using the in-built functionality of the site.



• All messaging is un-encrypted.

- 54 -



As part of Pornhub’s more extensive verification processes, for individual content creators, these

requirements are validated at least once per additional performer:



• Uploaders may meet the ID and consent verification requirement for their Co-performer in one of

the following ways:



o ID and liveness (biometric) test per above, plus signed consent form upload. Our internal

moderators review the result of the ID and liveness, and the terms of the consent form.



o Upload a photo and ID plus signed consent form. ID is validated by a third party ID

validation service, with our internal moderators verifying the result of the ID validation,

that the face of the co-performer matches the ID, and the terms of the consent form.



o IDand Releaseformpackage. Uploadcopies ofphoto, ID, andsigned consentformwhich

is then reviewed by internal moderators, verifying the face of the co-performer matches

the ID and the terms of the consent form.



o eSign (provided by Yoti). Co-performer undergoes ID, liveness (biometric) and performs

e-signatureofconsentform. Ifco-performer IDhas beenuploaded separately previously,

this option also supports reduced steps, with just the liveness and e-signature.



o Existing content creator. Where two or more registered and verified content creators

feature in the samecontent, they areableto tageachother, requiring affirmative consent.



• All co-performers must be approved by a member of the moderation team. All performers

appearing in uploaded content are checked by moderators against approved co-performers, to

ensure everyone appearing in content uploaded by content creators can be matched to an ID-

verified and approved co-performer. If there is any doubt then further documentation will be

requested from the uploader before the content is published. For example, if the content does

not feature a face that can be compared to the identity documents, then further images may be

required to ascertain that they are the same person. Ensuring identity and age of performers are

verified and validated beforepublication severely limits therisk ofpotentiallyillegalmaterialfrom

upload.



• Note, some older contenton the platformfellunder an older policy wherethe content creator was

required to attest to having ID and consent records for co-performers but before the company

began validatingeither one or both requirements for all content prior to publication. However, per

the timeline near the beginning of this document, we have announced a 30 June 2025 deadline

for individual verified uploaders to submit ID and consent paperwork for co-performers in

previously uploaded content. Older videos that do not meet our current verification requirements

will be removed from the platform by that date. For details, see our blog post.



• Content partners must first go through an on-boarding process (see Annex 1 – CPP Onboarding

Process v1.2).



• As it relates to content partners, Studio produced content follows record-keeping requirements

for age and identity verification under 18 U.S. Code § 2257, which requires creating and

maintaining individually identifiable records pertaining to every performer portrayed in a visual

depiction that comprises adult content.. While their website(s) and sample ID and consent

paperwork are audited at onboarding and annually they are not required to provide us with IDs for

- 55 -



all performers prior to content publication. This part of the verification process is managed by the

studios, and they are required to provide all documentation on demand:



o Content partners are required to go through a KYC process to validate their identity and

business. (see Annex 2 - KYC Process V1.1)



o All content partners go through an annual audit where they are required to provide

documentation for a random selection of their content.



• Further information on the verification process can be found in the following documentation:



o How to Sign Up and Join the Model Program – Pornhub Help , including the video tutorial

on this page



o Yoti Tech documentation: Overview - Yoti developer documentation



o Yoti Demo: Yoti Identity verification



• We have also now added INCODE as an additional identity verification provider.



• This robust process deters and helps to mitigate the risk relating to the upload of illegal material,

or committing any illegal acts on the platform.



o



Human checks of all removed content



• Any content which is reported or flagged for removal is investigated by a human support team.

The support team will contact the content creator if there is any doubt that the content is illegal

or does not have the consent of performers. This helps prevent over-blocking as a dialogue is

created with the uploader, giving them the chance to discuss the removal and provide anything

required by our support team in order to allow the content to be re-published.



• Content creators may also use this dialogue to appeal any decisionifthey are able to providenew

information that was not already considered when removing their content.

- 56 -



Gender-based violence, public health, minors, physical

and mental well-being

Negative effects in relation to minors

The effect ofpornography on minors is subject to an ongoingcomprehensivediscussionin psychology

and sociology. The same goes for the implications, including their advantages and disadvantages, of

some mitigating factors and in particular for the various forms of age verification. The essence of

these discussions is important to assess the risks as well as any mitigating factors appropriately. In

the following, wewill address themostrecent findingsregarding theseverity ofimpact ofpornography

on minors and also deal with the repercussions and risks related to different forms of age verification.

Both topics – severity of impact as well as certain adverse consequences of age verification – are

closely related as care must be applied to not increase the overall risk exposure of minors by applying

inappropriate forms of age verification.



1. Effect of Pornography on Minors according to latest Studies



Whilst there is wide agreement that pornography is not suitable for minors in general, the specific

impact on different groups of minors (adolescents and pre-adolescents in particular) as well as their

different level of exposure is relevant for a subsequent risk evaluation as well as the appropriate

mitigating factors.



• In her book of 2023 Porno – an Analysis without Shame, Madita Oeming addresses the effects of

pornography on society and individuals in a very comprehensive manner. Chapter IV (page 82

onwards) deals with the effects on minors and is summarized as follows (page 91):

“The findings show that young people are aware of pornography and specifically seek it out.

Porn is not a niche phenomenon, but a widespread form of adolescent media use. Pre-

pubertal children, however, rarely actively search for pornographic content and contact, if at

all, tends to be unintentional. Their own interest usually awakens with the onset of puberty,

increases continuously and then often levels off again in adulthood. Just like the age of onset,

the extent of adolescent porn use is often overdramatized in the media. Although porn is part

of the realities of young people's lives, it is not a primary topic of conversation for them and

plays a rather subordinate role compared to other media offerings such as Instagram, TikTok

and YouTube formats or computer games such as FIFA or Fortnite.”



• In a similar vein, the British Board of Film Classification (BBFC) determines it in its 2020 study

Young People, Pornography \& Age Verification (British Board of Film Classification (BBFC),

January 2020, Young people, pornography \& age-verification page 30):



“Many young people in the qualitative research turned to pornography to understand sex and

what it might entail” (p. 30).



• A similar observation follows from Smahel, D., Machackova, H., Mascheroni, G., Dedkova, L.,

Staksrud, E., Ólafsson, K., Livingstone, S., and Hasebrink, U. (2020). EU Kids Online 2020: Survey

results from 19 countries. EU Kids Online. Doi: 10.21953/lse.47fdeqj01ofo, p. 93, concluding:



“As the results showed, a substantial number of children were positive about their

experience. This is also in line with the presumption that children use the internet to fill their

developmental needs.”

- 57 -



Whilst this does not suggest that pornographic content is suitable for minors, it does indeed

suggest that any potentially negative implications do not seem to be perceived as such.



• In addition, in times of a generally heteronormative society, queer teenagers are often neglected,

thus one of the only support in ascertaining and confirming their identity and place in society is

pornographic content. The BBFC study confirms this by stating "almost half of all LGB

respondents felt that pornography had helped them to understand their sexuality" (p. 34).



2. Repercussions and Implications of different Forms of Age Verification



There are different methods of verifying the age of a website user. Those methods currently available

on the market that provide a high degree of certainty that a given user is indeed of age, will either need

to verify the user’s identity (either directly or by means of a third party verifying agent) or apply AI

based, real time biometric screening. Applying either of these methods will typically have the

following implications:



• According to all available evidence and as for example shown by the UK survey of the YouGov

institute, the greatmajority ofall users(78 % in the case ofthe UKsurvey)are unwillingto undergo

any such formof age verification on adult platforms, see Alohapressrelease. Our own experience

proves the same point: The implementation of strict age verification through ID checks on

Pornhub for users residing in Louisiana on 1 January 2023 lead to an immediate loss of over 80%

of our traffic.



• The users leaving Pornhub when required to do age verification do not simply stop watching

pornography. They instead go to any one of a thousand other available online offerings without

any protection of minors, and typically also without any other protections against other forms of

risks. This migration of user traffic to other adult sites – caused by such a strict age verification

process of the most protective site, such as Pornhub – is much more harmful for affected minors,

as to the best of our industry knowledge, almost every single one of the thousands of alternative

available sites offering pornographic content is less regulated, as well as less compliant, than

Pornhub. Most of these providers of adult content have no measures in place at all to protect

minors and ensure a safe and legal environment for their users. That is in clear contrast to

Pornhub’s own compliance, shown by our range of robust trust \& safety measures. The Canadian

Centre for Child Protection also noted that our reporting options, which have since improved

further, were better than many mainstream platforms, set out in Canadian Centre for Child

Protection, 2020, Reviewing child sexual abuse material reporting functions on popular

platforms, p. 10.



• In addition to such mass migration to significantly less compliant and outright non-compliant

sites, strict age verifications implemented in certain jurisdictionscould be circumvented by using

VPN-clients, which studies have proven to be known by minors nowadays (see Newswire Article,

quoted above and British Board of Film Classification (BBFC), January 2020, Young people,

pornography \& age-verification, p. 56).



• Independent from the points just raised above, strict age verification systems are also in conflict

with existing data protection laws in the EU and in particular the GDPR. Collecting detailed

personal user information at site level undermines the principles of data minimization, Art. 5 and

25 GDPR. Several data protection authorities in the EU have made this point already:



o For example, the French data protection authority Commission Nationale de

l'Informatique et des Libertés (CNIL) states in its publication of 22 September 2022

- 58 -



regarding Online age verification: balancing privacy and the protection of minors: "The

CNIL has analysed themain typesof ageverification systems in order to clarify its position

on age verification on the Internet, particularly on pornographic sites for which such

verification is mandatory. It specifies how such publishers could fulfil their legal

obligations. However, CNIL finds that such current systems are circumventable and

intrusive, and calls for the implementation of more privacy-friendly models."



o A similar conclusion was drawn from the English data protection authority back in 2017

regarding the Digital Economy Act and the implementation of strict age verification

systems, as this article shows: "With the passing of the Digital Economy Act 2017, the

United Kingdom became the first country to pass a law containing a legal mandate on the

provision of an Internet age verification system. Under the act, websites that published

pornography on a commercial basis would have been required to implement a "robust"

age verification system to prevent minors from accessing their sites. [...]. Key issues with

the implementation included what constituted an effective means of age verification, as

well as concerns over the possibility that online age verification providers could collect

excessive personally identifiable information and process it for other purposes—

potentially in violation of the General Data Protection Regulation (GDPR)."



o The privacy risks of age verification were highlighted recently by the Australian

government who decided not to proceed with mandatory platform-level age verification.

As well, in 2023 Texas introduced a law whose stated goal was to prevent the publication

or distribution of sexual material to minors on the internet to prevent minors from

accessing age-restricted content on the internet. A US Federal Judge in Texas rightly

found that the bill's age verification process, other restrictions and information

requirements violated Texans' freedom of speech, raised privacy concerns, and was

overly broad and vague. A similar law targeting social media platforms in Arkansas was

also judged unconstitutional around the same time.



o In Spain, the national Data Protection Authority published in its Decalogue an

endorsement of device level age verification methods – specifically with a view to the

privacy concerns of platform based strict age verification methods: “It is also necessary

to remove, from the design, the impact that personal data breaches of third-party

verification services or Internet services could have on minors. A possible solution is to

process the identity information, the "authorized to access" condition and the

execution of access limitation policies on the devices held by users without relying on

the servers of the service providers or third parties. In this sense, the requirements of

Article 25.2 of the GDPR regarding the minimization of personal data must be

considered.”); “The system for protecting minors from inappropriate content must

prevent third entities from acting as intermediaries between the user and the Internet

service provider using strategies that allow identification, browsing monitoring and/or

profiling of the person. This could be achieved, for example, by providing tools so that

the personal device is the one that executes all the verification mechanisms without

using external resources, including the execution of content access limitation

policies on the same device. Another strategy could be that the identity providers

provide accreditation of the “authorized to access” condition unlinked with the user

identity, thattheaimto accessadult contentis not linked to theuser, andthattheprocess

to get the accreditation does not generate meta-information linked to the person.”; and

“Executing accessrestrictionslocally onInternet users' deviceswould eliminate the

risks of profiling or monitoring” (page 8; in bold by us).

- 61 -



• The RTA-Label is therefore enormously better suited for the protection of minors than strict age

verification systems (i.e. identity verifying systems). Strict age verification systems can be

circumvented by using VPN-clients. In contrast, RTA-Labels work independently of the user’s IP

address or location, as they filter content based on categorization.



Age verification by self-declaration



• As mentioned above, we furthermoreapply a self-declarationmethod to verify a user’sagebefore

a user can access the content on our site:

• The required statement confirms our users’ adherence with the requirements of our Terms of

Service, which require all users to be at least 18 yearsold, or the ageofmajority in their respective

jurisdiction (where that should be higher), see https://www.pornhub.com/information/terms. In

addition, the age confirmation requirement also serves as a psychological deterrent, cautioning

minors to act in a compliant manner and refrain from accessing Pornhub.



Sexual Wellness Center



• Our Sexual Wellness Center deals with many sexual health topics in an open, honest, and

educational manner. It contains hundreds of articles from leading experts, written specifically for

the Center. The Center’s main contributor, Dr Laurie Betito, conducts multiple Q\&As and hosts a

podcast on a variety of sexual health subjects using questions posed by visitors to the site.

Regarding protection of minors: the Sexual Wellness Center on the platform is thus a great

possibility for minors interested in sexual education to inform and educate themselves without

the necessity to consume pornographic content.



Future mitigation measures



We believe that the real solution for protecting minors and adults alike is to verify users’ ages at the

point of access – the users’ devices – and to deny or permit access to age-restricted materials and

websites based on that verification\*.



This approach requires working with operating system companies and, with their buy-in, stands to

minimize the transmission of personal data while protecting minors from age -restricted content

across the entire internet.



We support device-level age verification because it would control the severe risks inherent with

potentially having hundreds of thousands of sites introducing and holding their own age verification

systems and require consumers to repeatedly present their ID or undergo biometric processing.



The technology to accomplish this exists today. Many devices already offer free and easy-to-use

parental control features that can prevent minors’ accounts from accessing adult content without

risking the disclosure of sensitive user data. These features simply need to be mandated to block

devices by default, unlocked only by age verification by an adult on the device.



Apple introduced age verification into their services. According to Apple’s announcement, as of fall

2023, “businesses will be able to accept IDs in Apple Wallet — no additional hardware needed. This

will streamline their ability to securely check a customer’s age in person for things like alcohol

purchases or to verify a customer’s identity at checkout for car rentals, and more.”

- 62 -



We support the “opt-out” approach wherein age-based blocks on inappropriate content would be

default-on and would require a verified adult to turn the filter off. This far exceeds the current “opt-in”

patchwork approach in which only a fraction of sites hosting age-restricted content have any kind of

age-gating or content-blocking options available to help parents effectively block their children from

accessing.



The device level solution is 360-degree solution that stops age-restricted content at the source and

protects a user’s privacy by not requiring users to provide their PII on multiple -sites across the

internet.



Age verification at the device level provides the strongest protection possible to block minors from

accessing inappropriate sites, protects adult user privacy, and is enforced equitably across all

platforms.



\*Device-Based Age Verification refers to any approach to age verification where the personal

information that is used to verify the user’s age is either shared in-person at an authorized retailer,

inputted locally into the user’s device, or stored on a network controlled by the device manufacturer

or the supplier of the device’s operating system. Whether through pre-installed content blocking and

filtering software, the disabling of web-browsing permissions, or other means, the user will then be

prevented from accessing age-restricted content over the internet unless they are age-verified. To

come to fruition, such an approach requires the cooperation of manufacturers and operating-system

providers.“

- 64 -



o Podcast: Is Porn Addiction Real? In this episode of the podcast, Dr. Laurie discusses the

question, “Is Porn Addiction Real?

o Podcast: Sex Addiction Is On The Rise In this podcast episode, Dr. Laurie discusses how

sex addiction is on the rise with guest David Essel.



o Understanding Sex Addiction This video challenges the use of the words “sex addict” and

explains why sex addiction, at least as a mental health definition, does not exist as well

as how it stigmatizes any sex that is deemed “wrong” by our culture. Instead, I talk about

sexual behavior that feels out of control, what to do about it, and how to get support from

a professional who will not shame diverse sexual practices.



o Q\&A With Dr. Laurie: When Does It Go Too Far?

- 66 -



• Regarding relationships the center contains:



o Is Porn Cheating? Watching porn can be great and even fun if you view it as a movie, and

if everyone in the relationship is okay with it. However, if you notice your partner sneaking

around to view porn, it would be good to discuss “is porn cheating?” instead of accusing

him/her of cheating. Remember that communication in the relationship is the most

important thing, and don’t be afraid to askfor professional help ifyou think it is necessary.

- 68 -



automatically removed from the platform. This further reduces the likelihood of violent material,

even in written form, from appearing on the platform.



Human moderation



• All uploaded images and videos are reviewed by at least one human moderator before being

published on the platform. Human moderators check that the IDs provided by uploaders and

performers match those within the material. If there are any concerns, then the moderator will

reach out to the uploader to supply more information and documentation. Human moderators

use the results from all tools to assist them in assessing the content and only publish material

once they are confident that the material does not violate our policies and guidelines. Requiring

moderation of all images and videos before publication, severely limits the likelihood of any

foreign interference.



Content Removal Request



• A content removal request form (CRR) is linked at the bottom of every page on the platform. All

visitors to the platformcan use theCRR to reportmaterialby providing the URL ofthe content, the

reason why it should be removed, and an email address so that the platform can communicate

with the reporter, ask for more detail if required, and confirm our decision. Content reported in

this manner is immediately and automatically removed, once the reporter has confirmed their

email address. This reduces the risk of viewing material and limits harm to victims.



Content Flagging



• The platform offers another way for logged-in users to flag all images, videos, comments, and

users. Content flagged in this manner will be reviewed by a moderator within just a few hours and

de-published if it is found to violate our Terms of Service. This reduces the risk of viewing material

and limits harm to victims.



Law enforcement portal



• We host a law enforcement portal so that law enforcement is able to quickly request information

from the platform to assist with legal cases.



Freedom of Sexual Expression



• When acted out by consenting adults in safe environments and adhering to our Terms of Service,

desires, fetishes and fantasies are welcomed and supported on our platform. Pornography does

not always represent sexual interactions and behaviours typical of everyday life, and can depict

diverse fantasies and role-play by consenting amateurs and professionals.



Sexual Wellness Center



• Our Sexual Wellness Center deals with many sexual health topics in an open, honest, and

educational manner. It contains hundreds of articles from leading experts, written specifically for

the Center. The Center’s main contributor, Dr Laurie Betito, conducts multiple Q\&As and hosts a

podcast on a variety of sexual health subjects using questions posed by visitors to the site.



• Regarding abuse the Center contains: How To Date After An Abusive Relationship.

- 69 -



Other resources



• As violent and abuse content is also likely to be non-consensual, please also see our risk

assessment on non-consensual content (NCC).

- 71 -



• Our Sexual Wellness Center deals with many sexual health topics in an open, honest, and

educational manner. It contains hundreds of articles from leading experts, written specifically for

the Center. The Center’s main contributor, Dr Laurie Betito, conducts multiple Q\&As and hosts a

podcast on a variety of sexual health subjects using questions posed by visitors to the site.



• Regarding unrealistic expectations the Center contains:



o Q\&A With Dr. Laurie: Expectation Vs Reality (pornhub.com)



o Q\&A With Dr. Laurie: Fantasy Vs. Reality (pornhub.com)

- 73 -

- 75 -



• As detailed in our guidelines, a user can turn off personal recommendations by selecting the

option in the hamburger menu on the platform. (See Recommender System Guidelines

(pornhub.com))