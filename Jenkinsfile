@Library("jenkins-library@docker-pipeline") _

helmChartPipeline(
    script: this,
    charts: ["filebeat", "logstash", "elasticsearch", "kibana"],
    version: "8.1.0-test",
    slackChannel: "#kubernetes"
)
