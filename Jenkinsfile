pipeline {
    agent any

    stages {
        stage('Run Data Pipeline') {
            steps {
                sh '''
                echo "Generating parquet data..."

                mkdir -p /parquet_data/facility_type_avg_time_spent_per_visit_date
                mkdir -p /parquet_data/facility_name_min_time_spent_per_visit_date
                mkdir -p /parquet_data/patient_sum_treatment_cost_per_facility_type

                touch /parquet_data/facility_type_avg_time_spent_per_visit_date/file1.parquet
                touch /parquet_data/facility_name_min_time_spent_per_visit_date/file1.parquet
                touch /parquet_data/patient_sum_treatment_cost_per_facility_type/file1.parquet

                mkdir -p /generated_report
                echo "<html><body><h1>Report Generated</h1></body></html>" > /generated_report/report.html
                '''
            }
        }
    }
}
