torchrun --nnodes=2 --nproc_per_node=1 --node_rank=0 --master_addr=spark-master --master_port=2222 main.py run --num_workers=4 --batch_size=64
