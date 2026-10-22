# Module 2: Crime Scene Investigation Evidences

*CCC (Certified Cyber Criminologist) - Virtual Cyber Labs - personal study notes of Samir Raja (CYBER07). Written in simple words with real-life examples. Original wording - my own study notes, not a copy of any course slides.*

## 1. Why Evidence Frameworks Exist

**In simple words:** A framework is a fixed rulebook for handling evidence - how to collect it, document it, pack it, store it, and produce it in court. Evidence is the backbone of every case, but digital evidence is fragile: it can be changed silently, deleted in seconds, or challenged by the defence. The framework exists so that evidence collected at a crime scene on day one is still strong and believable in a courtroom years later.

**Real-life example:** An officer seizes a suspect's phone and, out of habit, opens the gallery to 'check'. In court, the defence argues the data could have changed after seizure - and the judge agrees the evidence is doubtful. Nothing about the crime changed; only the handling was wrong. The framework prevents exactly this failure.

**Key points:**
- The framework serves everyone at once - police, forensic experts, courts, and the accused.
- It applies across fields: law enforcement, forensics, and cybersecurity all use the same discipline.
- Done right, it upholds three big things: the rule of law, justice being served, and public trust in the system.

## 2. The Five Objectives of the Framework

**In simple words:** Every evidence framework is built to achieve five objectives. Think of them as five promises the investigator makes to the court before touching a single device:

**Real-life example:** None

**Key points:**
- <b>1. Maintaining integrity:</b> evidence must stay exactly as it was found. No contamination, no tampering, no alteration - from the moment of collection to the moment it is shown in court.
- <b>2. Ensuring authenticity:</b> the evidence must be provably genuine. The chain of custody - a written record of every hand it passed through - is what proves it.
- <b>3. Admissibility in court:</b> evidence collected by the book is far more likely to be accepted by the judge, because it meets the legal standards of relevance, reliability, and authenticity.
- <b>4. Protecting rights:</b> correct procedure respects the rights of individuals, including privacy and due process. Respecting rights also makes the whole investigation more credible.
- <b>5. Enhancing investigation:</b> a clear framework removes guesswork, speeds up the work, and leads to more successful investigations and prosecutions.

## 3. The Eight Key Components

**In simple words:** The framework stands on eight working components. Miss any one of them and a gap appears that the defence can attack:

**Real-life example:** SOPs are like a recipe in a kitchen. Ten different cooks following one recipe produce the same dish every time. Ten investigators following one SOP produce evidence handled the same correct way, every time - no personal shortcuts.

**Key points:**
- <b>SOPs (Standard Operating Procedures):</b> clearly written steps for collection, handling, and storage, so the work is consistent and nothing is forgotten.
- <b>Chain of Custody:</b> a continuous record of who held the evidence at every stage. It establishes continuity and blocks any claim of tampering.
- <b>Documentation:</b> detailed notes, photographs, and sketches that freeze the evidence's condition and location at the moment of collection.
- <b>Packaging and storage:</b> the right materials and conditions, so evidence does not get contaminated, damaged, or degraded over time.
- <b>Expertise and training:</b> only trained people should collect evidence - they know the procedures, the legal requirements, and the traps.
- <b>Technological considerations:</b> digital evidence needs special handling - imaging, hashing, and protection from silent changes that physical evidence never faces.
- <b>Legal and ethical compliance:</b> every step must follow the law and ethical guidelines, or the credibility of the whole investigation suffers.
- <b>Quality control:</b> regular reviews and audits of the process, so mistakes are caught and the system keeps improving.

## 4. Digital Evidence: What to Look for in Each Crime

**In simple words:** Different crimes hide their proof in different corners of a device. An experienced investigator walks in already knowing what to look for - this map is the heart of this module:

**Real-life example:** In a phishing case, the investigator does not read the whole phone. She goes straight to the e-mails, the internet activity logs, and the financial records - because that is where this crime leaves its footprints. Knowing the map saves hours and avoids missing the one file that matters.

**Key points:**
- <b>Computer fraud:</b> chat logs, e-mails, accounting software and files, databases, credit card data, customer information, auction account data.
- <b>Child abuse material investigations:</b> images and movie files, chat logs, internet activity logs, graphic editing software, user-created folder names that classify images.
- <b>Network intrusion:</b> IP addresses and usernames, configuration files, executable programs, source code, internet relay chat logs, text files holding usernames and passwords.
- <b>Homicide:</b> telephone records, diaries, maps, photos of victim and suspect, medical records, legal documents and wills, financial records.
- <b>Domestic violence:</b> diaries, e-mails, telephone records, financial asset records.
- <b>Financial fraud and counterfeiting:</b> currency images, cheque and money-order images, images of signatures, bank logs, credit card numbers, false identification, online banking software.
- <b>E-mail threats, harassment and stalking:</b> e-mails, internet activity logs, telephone records, images, victim background research, maps to victim locations.
- <b>Narcotics:</b> drug recipes, prescription form images, databases, calendars, false IDs, financial records.
- <b>Software piracy:</b> software serial numbers, cracking utilities, chat logs, images of software certificates, folders classifying pirated software.
- <b>Telecommunication fraud:</b> cloning software, electronic serial numbers, mobile identification numbers, customer database records.
- <b>Identity theft:</b> card reader/writers, scanner and camera software, ID templates (birth certificates, driving licences, signatures), counterfeit cheques and documents, deleted documents, online order and trading records.
- <b>The common thread:</b> address books, e-mails, and internet activity logs appear in almost every investigation - check them first, always.

## 5. Seizing Tools: The Hardware Kit

**In simple words:** Software alone cannot safely seize evidence - the wrong click can write changes onto a suspect disk and destroy its value. That is why forensic work uses specialised hardware tools whose only job is to take data out without changing anything:

**Real-life example:** A write blocker works like a one-way valve. Data flows out of the suspect's drive into the investigator's machine, but not a single bit can flow back in. The original stays frozen in time, exactly as it was seized.

**Key points:**
- <b>Write blockers:</b> hardware that blocks every write operation to the storage media. The drive can be read and imaged while the original data remains untouched.
- <b>JTAG / chip-off tools:</b> for devices that are locked, damaged, or unsupported. The examiner connects to test points on the circuit board (JTAG) or physically removes the memory chip (chip-off) and reads the data directly.
- <b>Cellular forensics devices:</b> built for mobile phones. They support logical extraction (data visible through the operating system) and physical extraction (raw data straight from memory).
- <b>SIM card readers:</b> pull contacts, call logs, and SMS messages stored on the SIM card itself.
- <b>Embedded device forensics tools:</b> specialised tools for embedded systems, IoT devices, and industrial control systems, whose unusual architectures defeat normal methods.

## 6. The Five Rules of Evidence

**In simple words:** Before any evidence is trusted, it is judged against five rules. Learn these five words - almost every courtroom fight over digital evidence comes back to one of them:

**Real-life example:** Think of the court as a strict examiner. Evidence that fails even one rule is like an answer written in pencil with pages missing - it may be true, but nobody is obliged to accept it.

**Key points:**
- <b>Admissible:</b> the evidence meets the legal standards to be included in court proceedings at all.
- <b>Authentic:</b> it is proven genuine and truly represents the source it claims to come from.
- <b>Complete:</b> all relevant information is presented - no tunnel vision, no cherry-picking only the parts that suit one side.
- <b>Reliable:</b> it is trustworthy and consistent with the facts and with the methods used to collect it.
- <b>Believable:</b> it is credible - free of contradictions and bias, so the court can rely on it.

## 7. Hashing, Authentication and Acquisition

**In simple words:** Three technical ideas hold up all of digital evidence. Hashing proves the data never changed, authentication proves who someone is, and acquisition is the act of copying evidence the safe way:

**Real-life example:** Hashing is a file's fingerprint. Two people can share a name, but never a fingerprint. In the same way, two different files can never share the same hash - and if even one letter inside the file changes, the fingerprint changes completely.

**Key points:**
- <b>Hashing:</b> a mathematical process that converts any data - a file, a message, a whole disk image - into a fixed-length string of characters called a hash value. The hash is unique to that exact data. Change even a tiny part of the input and the output changes completely, which makes hashing perfect for proving that evidence was never altered.
- <b>Authentication:</b> the process of verifying identity - proving that a person, system, or entity is who it claims to be. Passwords, biometrics like fingerprints and face recognition, and digital certificates are all authentication tools. It keeps unauthorised people away from sensitive data.
- <b>Acquisition:</b> the forensically sound copying of data from a device or storage medium. The output is a forensic image - an exact copy of the original, including all data, metadata, and structure. Different devices and media need different acquisition methods, but the rule never changes: the original must not be altered.

## 8. Evidence Preservation: The Five Methods

**In simple words:** Collecting evidence correctly is only half the job. It then has to survive months or years of storage, transport, and court dates without losing its value. Five preservation methods make that happen:

**Real-life example:** Picture the evidence room of a police station. Every item sits in a labelled, sealed packet; a register records everyone who touches it; and for digital evidence, a hash value is written on the file so any change would be caught instantly. That room is these five methods in action.

**Key points:**
- <b>Chain of custody:</b> a meticulous record of who handled the evidence, when, and for what purpose. This unbroken trail is what keeps evidence admissible.
- <b>Proper packaging:</b> appropriate materials and containers for each evidence type, preventing contamination, damage, or alteration during storage and transport.
- <b>Secure storage:</b> controlled environments that protect evidence from environmental damage, tampering, and unauthorised access. Digital evidence, physical objects, and biological samples each need their own conditions.
- <b>Digital hashing:</b> hash values are calculated and stored at the time of acquisition, then re-verified regularly. Any unauthorised modification shows up immediately.
- <b>Documentation:</b> thorough notes, photographs, and sketches of the evidence's condition, location, and details at collection time - the permanent reference for everything that follows.

## 9. Offences and Penal Sections

**In simple words:** Every cybercrime maps to specific sections of the law - mainly the IT Act 2000, supported by the IPC and special acts. When you write an FIR or a report, the section numbers are what give your complaint its legal teeth. This table is the module's ready reckoner: complaint on the left, punishment on the right.

**Real-life example:** A fake bank e-mail asks victims for login credentials. That single act is 'cheating by personation using a computer' - Section 66D of the IT Act (3 years / Rs 1 lakh) plus Section 419 IPC (3 years). One crime, two laws, both applied together.

| # | Offence / complaint | IT Act 2000 | Other laws |
|---|---|---|---|
| 1 | Mobile phone lost or stolen | - | IPC 379 - up to 3 yrs / fine / both |
| 2 | Receiving stolen computer, mobile phone or data | IT 66B - 3 yrs / Rs 1 lakh / both | IPC 411 - 3 yrs / fine / both |
| 3 | Your or your company's data stolen (any form) | IT 66 - 3 yrs / Rs 5 lakh / both | IPC 379 - 3 yrs / fine / both |
| 4 | Password stolen and used for a fraudulent purpose | IT 66C + 66D - 3 yrs / Rs 1 lakh each | IPC 419 - 3 yrs; IPC 420 - 7 yrs |
| 5 | E-mail read by someone using your password fraudulently | IT 66 - 3 yrs / Rs 5 lakh; IT 66C - 3 yrs / Rs 1 lakh | - |
| 6 | Biometric thumb impression misused | IT 66C - 3 yrs / Rs 1 lakh | - |
| 7 | Electronic or digital signature misused | IT 66C - 3 yrs / Rs 1 lakh | - |
| 8 | Phishing e-mail sent in your name asking for credentials | IT 66D - 3 yrs / Rs 1 lakh | IPC 419 - 3 yrs / fine |
| 9 | Image of a private area captured or published without consent | IT 66E - 3 yrs / Rs 2 lakh / both | IPC 292 - 2 yrs + Rs 2,000 (repeat: 5 yrs + Rs 5,000) |
| 10 | Tampering with computer source documents | IT 65 - 3 yrs / Rs 2 lakh / both; IT 66 - 3 yrs / Rs 5 lakh | - |
| 11 | Data modification | IT 66 - 3 yrs / Rs 5 lakh / both | - |
| 12 | Sending offensive messages through a communication service | - (old 66A was struck down in 2015) | IPC 500 - 2 yrs; 504 - 2 yrs; 506 - 2 yrs (7 yrs if death threat); 507 - 2 yrs; 508 - 1 yr; 509 - 1 yr |
| 13 | Publishing or transmitting obscene material electronically | IT 67 - 1st: 3 yrs + Rs 5 lakh; repeat: 5 yrs + Rs 10 lakh | IPC 292 - 2 yrs + Rs 2,000 (repeat: 5 yrs + Rs 5,000) |
| 14 | Publishing material with sexually explicit acts electronically | IT 67 - 1st: 3 yrs + Rs 5 lakh; repeat: 5 yrs + Rs 10 lakh | IPC 292 - as above |
| 15 | Material depicting children in sexually explicit acts | IT 67B - 1st: 5 yrs + Rs 10 lakh; repeat: 7 yrs + Rs 10 lakh | IPC 292 - as above |
| 16 | Misusing a Wi-Fi connection against the State | IT 66 - 3 yrs / Rs 5 lakh; IT 66F - life imprisonment | - |
| 17 | Planting a computer virus against the State | IT 66 - 3 yrs / Rs 5 lakh; IT 66F - life imprisonment | - |
| 18 | Denial-of-service attack on a government computer | IT 66 - 3 yrs / Rs 5 lakh; IT 66F - life imprisonment | - |
| 19 | Stealing data from a government computer (national security) | IT 66 - 3 yrs / Rs 5 lakh; IT 66F - life imprisonment | - |
| 20 | Not allowing authorities to decrypt communications | IT 69 - up to 7 yrs + fine | - |
| 21 | Intermediary not giving authorities access to stored information | IT 69 - up to 7 yrs + fine | - |
| 22 | Failure to block websites when ordered | IT 69A - up to 7 yrs + fine | - |
| 23 | Sending threatening messages by e-mail | - | IPC 504 - 2 yrs / fine / both |
| 24 | Word, gesture or act insulting the modesty of a woman | - | IPC 509 - 1 yr / fine / both |
| 25 | Sending defamatory messages by e-mail | - | IPC 500 - 2 yrs / fine / both |
| 26 | Bogus websites and cyber frauds | IT 66D - 3 yrs / Rs 1 lakh | IPC 419 - 3 yrs; IPC 420 - 7 yrs + fine |
| 27 | E-mail spoofing | IT 66C - 3 yrs / Rs 1 lakh | IPC 465 - 2 yrs; IPC 468 - 7 yrs + fine |
| 28 | Making a false document | IT 66D - 3 yrs / Rs 1 lakh | IPC 465 - 2 yrs / fine / both |
| 29 | Forgery for the purpose of cheating | IT 66D - 3 yrs / Rs 1 lakh | IPC 468 - 7 yrs + fine |
| 30 | Forgery to harm reputation | IT 66D - 3 yrs / Rs 1 lakh | IPC 469 - 3 yrs + fine |
| 31 | E-mail abuse | - | IPC 500 - 2 yrs / fine / both |
| 32 | Criminal intimidation | - | IPC 506 - 2 yrs (7 yrs if threat of death or grievous hurt) |
| 33 | Copyright infringement | IT 66 - 3 yrs / Rs 5 lakh / both | Copyright Act 1957, Sections 63 and 63B |
| 34 | Theft of computer hardware | - | IPC 379 - 3 yrs / fine / both |
| 35 | Online sale of drugs | - | NDPS Act |
| 36 | Online sale of arms | - | Arms Act |

**2026 update - read this carefully:** From 1 July 2024, the IPC has been replaced by the Bharatiya Nyaya Sanhita (BNS). The table above uses IPC numbers, which still apply to offences committed before that date; new offences are booked under BNS. Key equivalents: theft 379 IPC = BNS 303; receiving stolen property 411 = BNS 317; cheating by personation 419 = BNS 319; cheating 420 = BNS 318; defamation 500 = BNS 356; intentional insult 504 = BNS 352; criminal intimidation 506 = BNS 351; insulting a woman's modesty 509 = BNS 79; obscenity 292 = BNS 294; forgery 465/468/469 = BNS 336. The IT Act 2000 sections are unchanged. Also note: Section 66A of the IT Act was struck down by the Supreme Court in 2015, which is why 'offensive messages' in the table carries only IPC/BNS sections.
