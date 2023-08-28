times_config.py 파일에서 모델 hyperparameter tunning 가능
column 수에 따라서 self.c_out = , self.enc_in =  조정

train validation test csv files의 경로지정. 
필요할 경우 train validation test를 여러개 쓸 수 있음.
예: --train_path '첫번쨰 데이터 경로' '두번쨰 데이터 경로' '세번째 데이터 경로'

python 'times_traintest.py' --train_path 'path.csv' --val_path 'path.csv' --test_path 'path.csv' --lr 0.001 --epochs 1 --batch_sizes 2
스크립트 실행이후 현재 경로에 results.csv가 자동저장됨. 

colab_example.ipynb   
colab_example.py  참고   
