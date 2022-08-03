@Library("jenkins-library@docker-pipeline") _

helmChartPipeline(
    script: this,
    charts: ["perch-chart", "perch-service-mesh-chart", "sales-agent-chart", "sales-agent-service-mesh-chart",
      "perch-cluster-infra-chart", "backoffice", "filebeat", "logstash", "elasticsearch", "kibana"],
    version: "8.1.0",
    slackChannel: "#kubernetes"
)
