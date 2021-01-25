---
title: Your genome isn't private. Maybe it never was.
description: There’s plenty at Defcon to be paranoid about―unencrypted smart homes, mysterious telephone surveys, tiny murderous drones, insecure voting machines, and (at least around the Biohacking Village) genetic privacy. Is such paranoia justified
date: 2018-09-18
permalink: blog/defcon-biohacking-genetic-privacy/
tags:
  - posts
  - conference-report
layout: layouts/post.njk
---

_Tessa Alexanian's report from the Defcon Biohacking Village_

Every summer, Defcon brings together tens of thousands of black-shirted hackers to defy the hair-dryer heat of Las Vegas. There’s plenty at Defcon to be paranoid about: unencrypted smart homes, mysterious telephone surveys, tiny murderous drones, insecure voting machines, and (at least around the [Biohacking Village](http://villageb.io/)) genetic privacy.

Hackers generally view privacy as axiomatically necessary; the speakers at Defcon didn’t really address why one should be paranoid about protecting genetic information. Is such paranoia justified?

Well, discrimination on the basis of genes is already a reality— China has introduced mandatory whole genome sequencing as part of its selection process for Olympic athletes. Laws have been introduced to prevent prohibitive insurance premiums based on disease risks encoded in DNA. Scientists [know](https://blogs.scientificamerican.com/cross-check/code-rage-the-warrior-gene-makes-me-mad-whether-i-have-it-or-not/) that the “warrior gene” is over-hyped, but the popular media seems intent to speculate about harsher sentencing based on its weak predictions of aggressive behaviour. Our predictions are improving, though— we’re not far from predicting scientifically (and socially) complex traits like [cognitive ability](https://infoproc.blogspot.com/2017/08/ninety-nine-genetic-loci-influencing.html) through aggregating hundreds of genetic variants.

Many countries prohibit genetic discrimination, but not as extensively as one might think. Europe protected genetic privacy just this year in the GDPR, Canada’s GDA law only came into force in 2017,and the USA’s 2008 GINA law doesn’t cover discrimination in life or disability insurance. Given these imperfect and [perhaps impermanent](https://blogs.plos.org/dnascience/2017/03/09/saving-gina-is-genetic-privacy-imperiled/) legal protections around genetic privacy, a bit of paranoia seems justified.

If you wanted to get a consumer genetics test, you could try to protect your privacy by carefully separating your test results from your identity: use a pseudonym, pay with a prepaid credit card, ship your results to a commercial address— that sort of thing. Such precautions were originally going to be the topic of [AlmostHuman](https://twitter.com/almosthuman0x1)’s talk at Defcon. After researching the talk, and with obvious reluctance, he titled it _No Firewall Can Save You At The Intersection Of Genetics and Privacy_.

AlmostHuman speaks about consumer genomics services and privacy.

He was particularly shaken by the way genetic data was used in the Golden State Killer case. In April 2018, the police arrested a suspect who had never had his DNA sequenced. Investigators uploaded a sample from an old rape kit to GEDmatch, a genealogy website that allows people to search for relatives using DNA sequences. The site gave them a set of great-great-great grandparents and the investigators used public demographic data to branch out potential family trees. They knew the rough age and location of the suspect from thirty-year-old witness testimony. This was enough to narrow their search down to a single man, even though neither he nor any of his immediate relatives had made their DNA public.

So no firewall could save your genetic privacy. You share too much with your family. In fact, in 2003 [the Icelandic supreme court found](https://www.nature.com/articles/429118b) that a woman could opt out of her father’s genome being uploaded to their national genetic database. That ruling didn’t prevent the database from expanding— [by 2014](https://www.bbc.com/news/magazine-27903831), the database contained information from one third of Icelanders. In the USA, at the start of 2018, consumer genetics companies had [already tested the DNA](https://www.technologyreview.com/s/610233/2017-was-the-year-consumer-dna-testing-blew-up/) of more than 12 million people. That’s roughly 1 in 25 American adults— chances are a limb of your own family tree is already captured in some company database. There are enough public genealogy databases that someone with access to your genetic information (which they could obtain with a single hair and a thousand dollars) could track down your identity the same way those investigators did.

Can a genetics database both protect your privacy and provide genealogy services? Probably not. They can’t allow customers to search for relatives without exposing some genetic data. However, perhaps some [minimum standard of anonymization](https://news.mit.edu/2016/protecting-privacy-genomic-databases-0809) for consumer genetics companies would be prudent, especially as they share their internal genetic databases in [large-scale collaborations](https://www.wired.com/story/23andme-glaxosmithkline-pharma-deal/). Right now, American laws protecting personal health information don’t apply to these companies, who are regulated more as tech startups than healthcare providers.

Anne Kim: “Paranoia is fun!”

You might be out of luck even if no one in your family has sent off a cheek swab for sequencing. [Anne Kim](https://twitter.com/herroannekim)’s talk, titled _Selfie or Mugshot?_, discussed [a Nature paper](https://www.nature.com/articles/s41588-018-0057-4) from earlier this year in which researchers predicted facial structure using 38 genetic variants. She wondered if you could go in the opposite direction: take facial structure and predict a genome. Could a selfie of yours be used to fabricate DNA evidence against you?

Not quite yet. Extracting those variants and other demographics from your selfie would let a bad actor make a pretty good guess at your genome. With today’s technology, though, fabricating a realistic DNA sample based on that guess would cost hundreds of millions of dollars. It would be much easier and much, much cheaper to swipe one of your hairs and replicate its DNA. It is possible that someone might frame you by planting your DNA at a crime scene, but it won’t involve any elaborate hacking of your genetic information.

Setting aside forensic-drama plotlines, it’s worrisome that your DNA sequence can be partly derived from a publicly-shared selfie. The legislators who drafted the current laws against genetic discrimination probably weren’t picturing that scenario. That’s a shame— as DNA sequencing becomes cheaper and cheaper, and genetic information is more and more widely shared, all we can really hope for is that our insecure genetic data isn’t misused.

It’s still not a _bad_ idea to go through anonymizing precautions if you get a consumer genetic test; it’s just insufficient. We need to set out a minimum standard of anonymization for consumer databases, but then, that’s insufficient, too. There are complicated regulatory issues that must be addressed: should you have to get consent from your parents, siblings and children before making your DNA public? How can we avoid excessive insurance discrimination, while still ensuring that insurers have reasonable models of risk? If you want to get involved in the relevant advocacy, the [Electronic Frontier Foundation](https://www.eff.org/issues/genetic-information-privacy) has a detailed (though USA-centric) breakdown and posts relevant updates on its [blog](https://www.eff.org/deeplinks).

Your genome is as personal as information can be. But, to the dismay of the biohackers at Defcon, it could never have remained private. You leave traces of your DNA in every hair you shed and on every cup you hold. It leaves signs in the shape of your face, the way that you move, and how you are in the world. Too much of it is shared with your family for it to remain a secret. The problems of genetic privacy, to the further dismay of the more libertarian hackers, will have to be solved with regulation.

### Further reading

[Is Genetic Privacy a Myth?](http://protomag.com/articles/genetic-privacy-myth,) by Kristen French, _Proto_, September 2017. This article offers a more detailed and less hacker-focused discussion of the difficulty of protecting genetic information.

[Genetic Privacy](https://www.nature.com/news/genetic-privacy-1.12238), _Nature_, 493 (7433), January 2013. This editorial discusses research led by Yaniv Erlich showing that the anonymity of participants in scientific studies can easily be compromised by cross-referencing genealogical databases and “anonymized” genetic databases.

[GDPR and Me: how the EU data rules could impact genetic testing](https://readplaintext.com/gdpr-and-me-how-the-eu-data-rules-could-impact-genetic-testing-851494e55dd3), by Jennifer Huddleston Skees, _ReadPlainText_, May 2018. This article offers an opposing perspective that might allow you to better consider the trade-offs between consumer freedom, law enforcement, and genetic privacy laws.
