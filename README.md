everything fine-tuning
experiments where i try different strategies and familiarize myself

1. extract data from ultrafeedback and make sure we only get the prompt/answer responses with a rating above 5 in the benchmarks. extract in the right format

2. bad clustering. shows that we have a variance in prompt/answer 

3. instruction-response pairs that are ready for SFT

4. splitting dataset to sft into train/eval/test

5. select base model and do math for how perplexity metric will be used

6. using the lang model to generate ouputs. we will only do so on the eval set since we use that to benchmark
