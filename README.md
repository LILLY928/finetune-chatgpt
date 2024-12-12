The code is stored at:
    Batch_testing.ipynb
    Format_validation.ipynb
    Ft_v1.ipynb
    Ft_v2.ipynb

In this project we have three models, the baseline, the ft_v1, and the Ft_v2
1. The original dataset is and remained untouched
    nereus_dataset_biluo.txt
2. The following are the datasets that will be used as input for finetuning and testing
    output.jsonl
    train.jsonl
    v2_train.jsonl
    validation.jsonl
3. The following are the training results of ft_v1 and ft_v2, the graph is drawn based on the these two files
    Result.csv
    Result_v2.csv   
3. When evaludating the three models, we use the batch API to achieve large scale request. The files generated in this process are:
    Prepare the batch input files:
        Base_requests.jsonl
        Ft_requests.jsonl
        Ft_v2_requests.josnl
    Store the batch output files:
        Base_results.txt
        Ft_results.txt
        Ft_v2_results.txt
