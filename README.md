Feedback from users of the Pilly app indicated that entering medical information was excessively time-consuming. To address this, Panacea developed a web service that can interpret medication labels. This service enables users to take a photo of their medication label, upload it, and then the service identifies the medication and returns the relevant data.

This application, developed in Python, is hosted on Google App Engine. It utilizes the Google Vision API to recognize text within images. This text is subsequently cross-referenced with a database of medication names, which is compiled using the DailyMed (NLM) API.

Currently, the label reader is in the development phase and successfully interprets 65% of medication labels accurately.

