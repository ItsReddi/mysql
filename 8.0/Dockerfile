FROM mysql:8.0.37
CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_0900_ai_ci", "--sql_mode=NO_ENGINE_SUBSTITUTION", "--log-bin-trust-function-creators=true", "--event-scheduler=OFF", "--skip-log-bin", "--innodb_flush_log_at_trx_commit=0"]
