# AI-Generated-Text-Detector

Сеть, которая отличает сгенерированное нейросетью текст/эссе, от человеческого. 

Данные из соответствующего соревнования на kaggle https://www.kaggle.com/competitions/llm-detect-ai-generated-text/overview, также (дополнительно можно рассмотреть https://huggingface.co/datasets/artem9k/ai-text-detection-pile, https://commons.datacite.org/doi.org/10.6084/m9.figshare.24208443.v1)

Вопрос какие модели лучше использовать ещё прорабатывается. Рассмотрю как решали эту задачу на kaggle. В самых общих чертах схема: Encoder -> Classifier.

Финальное решение можно оформить в виде telegram-бота
