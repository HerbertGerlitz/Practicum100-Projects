# Investigation of the Users' Behavior for a Company's App
The Company selling Food Products has an App for its customers. We will investigate the event funnel and will analyse the results of an A/A/B Test. The Test is about the user behaviour when changing the set of fonts in the app. Will the new set of fonts be profitable for the company?

**Overview of the Data:**

The DataFrame consists of 244,126 rows and every row stands for a log entry. A log entry consists of a customer from one of the A/A/B test groups at a certain timestamp doing an action or experiencing an event. There are four columns:

- 'event_name': Consists of five possible user actions (events): 'MainScreenAppear', 'PaymentScreenSuccessful', 'CartScreenAppear', 'OffersScreenAppear' and 'Tutorial'.
- 'user_id': Consists of numbers that stand for certain customers.
- 'timestamp': Gives the timestamp of the event.
- 'group_id': Consists of three different groups: 246 and 247 are the control groups and 248 is the test group of the A/A/B test.
