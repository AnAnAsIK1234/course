# course
Изначально хотел обучить нейронку как экстрактор и сверху нацепить SVM или случайный лес
Но разница вроде как вышла небольшая, да и тем более не знаю, на каких новых данных будет
проверяться модель)). Поэтому в стандартной конфигурации при вызове My_Model() будет получена 
обычная VGG16. Но если вызвать My_Model(SVM_or_RandomForest="Forest",onlyNN = False) или вместо Forest - SVM модель будет использовать 
VGG16 как экстрактор, а само предсказание будет давать Forest или SVM, соответственно.

Из дополнительных пунктов выполнил все
Резульататы для My_Model на всех данных:

metrics for d_test_tiny:
	 accuracy 0.9111:
	 balanced accuracy 0.9111:

metrics for d_test_small:
	 accuracy 0.9411:
	 balanced accuracy 0.9411:

metrics for d_test_big:
	 accuracy 0.9458:
	 balanced accuracy 0.9458:
                  
