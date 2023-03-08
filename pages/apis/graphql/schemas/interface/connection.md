---
toc: false
---
<!--
  _____   ____    _   _  ____ _______   ______ _____ _____ _______
  |  __  / __   |  | |/ __ __   __| |  ____|  __ _   _|__   __|
  | |  | | |  | | |  | | |  | | | |    | |__  | |  | || |    | |
  | |  | | |  | | | . ` | |  | | | |    |  __| | |  | || |    | |
  | |__| | |__| | | |  | |__| | | |    | |____| |__| || |_   | |
  |_____/ ____/  |_| _|____/  |_|    |______|_____/_____|  |_|
  This file is auto-generated by script/generate_graphql_api_content.sh,
  please build the schema.json by running `rails api:graph:export`
  with https://github.com/buildkite/buildkite/,
  replace the content in data/graphql_data_schema.json
  and run the generation script `./scripts/generate-graphql-api-content.sh`.
-->
<!-- vale off -->
<h1 class="has-pills" data-algolia-exclude>
  Connection
  <span class="pill pill--interface pill--normal-case pill--large"><code>INTERFACE</code></span>
</h1>
<!-- vale on -->




<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Fields</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>count</code><a href="/docs/apis/graphql/schemas/scalar/int" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR Int"><code>Int</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>pageInfo</code><a href="/docs/apis/graphql/schemas/object/pageinfo" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT PageInfo"><code>PageInfo</code></a></h3></td></tr>
  </tbody>
</table>






<h2 data-algolia-exclude>Possible types</h2>
<a href="/docs/apis/graphql/schemas/object/agentconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT AgentConnection"><code>AgentConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/agenttokenconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT AgentTokenConnection"><code>AgentTokenConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/annotationconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT AnnotationConnection"><code>AnnotationConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/artifactconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT ArtifactConnection"><code>ArtifactConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/authorizationconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT AuthorizationConnection"><code>AuthorizationConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/buildconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT BuildConnection"><code>BuildConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/buildmetadataconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT BuildMetaDataConnection"><code>BuildMetaDataConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/changelogconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT ChangelogConnection"><code>ChangelogConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/clusteragenttokenconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT ClusterAgentTokenConnection"><code>ClusterAgentTokenConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/clusterconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT ClusterConnection"><code>ClusterConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/clusterqueueconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT ClusterQueueConnection"><code>ClusterQueueConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/dependencyconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT DependencyConnection"><code>DependencyConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/emailconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT EmailConnection"><code>EmailConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/jobconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobConnection"><code>JobConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/jobeventconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT JobEventConnection"><code>JobEventConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/organizationauditeventconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT OrganizationAuditEventConnection"><code>OrganizationAuditEventConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/organizationconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT OrganizationConnection"><code>OrganizationConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/organizationinvitationconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT OrganizationInvitationConnection"><code>OrganizationInvitationConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/organizationinvitationteamassignmentconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT OrganizationInvitationTeamAssignmentConnection"><code>OrganizationInvitationTeamAssignmentConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/organizationmemberconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT OrganizationMemberConnection"><code>OrganizationMemberConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/organizationmemberpipelineconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT OrganizationMemberPipelineConnection"><code>OrganizationMemberPipelineConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/pipelineconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT PipelineConnection"><code>PipelineConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/pipelinemetricconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT PipelineMetricConnection"><code>PipelineMetricConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/pipelinescheduleconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT PipelineScheduleConnection"><code>PipelineScheduleConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/ssoauthorizationconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT SSOAuthorizationConnection"><code>SSOAuthorizationConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/ssoproviderconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT SSOProviderConnection"><code>SSOProviderConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/suiteconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT SuiteConnection"><code>SuiteConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/teamconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT TeamConnection"><code>TeamConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/teammemberconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT TeamMemberConnection"><code>TeamMemberConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/teampipelineconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT TeamPipelineConnection"><code>TeamPipelineConnection</code></a>
<a href="/docs/apis/graphql/schemas/object/teamsuiteconnection" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT TeamSuiteConnection"><code>TeamSuiteConnection</code></a>