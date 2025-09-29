## Summary

Elasticsearch version: `9.2.0-SNAPSHOT`  
Elasticsearch build hash: `9316d644f0d45e9fcdcd827f2c63b26cbc211742`

| Total types | Validated | Failing | Missing test | Missing types |
| --- | --- | --- | --- | --- |
| 574 | 531 (92.5%) | 43 (7.5%) | 99 (17.2%) | 21 (3.7%) |

<details>
<summary>Breakdown by stability</summary>

|  | Total types | Validated | Failing | Missing test | Missing types |
| --- | --- | --- | --- | --- | --- |
| `stable` | 484 | 445 (91.9%) | 39 (8.1%) | 90 | 6 |
| `beta` | 24 | 21 (87.5%) | 3 (12.5%) | 0 | 0 |
| `experimental` | 66 | 65 (98.5%) | 1 (1.5%) | 9 | 15 |

</details>

<details>
<summary>Breakdown by visibility</summary>

|  | Total types | Validated | Failing | Missing test | Missing types |
| --- | --- | --- | --- | --- | --- |
| `public` | 0 | 0 (0%) | 0 (0%) | 0 | 0 |
| `feature_flag` | 0 | 0 (0%) | 0 (0%) | 0 | 0 |
| `private` | 0 | 0 (0%) | 0 (0%) | 0 | 0 |

</details>

<details>
<summary>Top 20 failing Cloud APIs</summary>

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `search` | :red_circle: | 2570/2640 | 2640/2640 | stable | undefined |  |
| `security.authenticate` | :red_circle: | 30/30 | 25/30 | stable | undefined |  |
| `indices.get_mapping` | :red_circle: | 228/228 | 215/228 | stable | undefined |  |
| `watcher.get_watch` | :red_circle: | 37/37 | 34/37 | stable | undefined |  |
| `watcher.put_watch` | :red_circle: | 46/53 | 53/53 | stable | undefined |  |
| `indices.put_mapping` | :red_circle: | 142/150 | 153/153 | stable | undefined |  |
| `indices.stats` | :red_circle: | 125/125 | 36/124 | stable | undefined |  |
| `indices.create` | :red_circle: | 1362/1402 | 1402/1402 | stable | undefined |  |
| `cluster.stats` | :red_circle: | 27/27 | 0/27 | stable | undefined |  |
| `xpack.usage` | :red_circle: | 45/45 | 2/41 | stable | undefined |  |
| `indices.put_index_template` | :red_circle: | 130/154 | 154/154 | stable | undefined |  |
| `indices.get_settings` | :red_circle: | 85/85 | 66/85 | stable | undefined |  |
| `ilm.explain_lifecycle` | :red_circle: | 5/5 | 4/5 | stable | undefined |  |
| `indices.update_aliases` | :red_circle: | 33/33 | 7/33 | stable | undefined |  |
| `indices.put_alias` | :red_circle: | 64/64 | 21/64 | stable | undefined |  |
| `indices.put_settings` | :red_circle: | 56/58 | 58/58 | stable | undefined |  |
| `cluster.put_component_template` | :red_circle: | 34/38 | 38/38 | stable | undefined |  |
| `indices.put_template` | :red_circle: | 45/46 | 46/46 | stable | undefined | deprecated |
| `nodes.stats` | :red_circle: | 58/58 | 21/58 | stable | undefined |  |
| `indices.get_data_stream` | :red_circle: | 124/124 | 77/124 | stable | undefined |  |
| **Summary** | :red_circle: | 97.1% | 93.6% | | | |

</details>

<details>
<summary>Table of Contents</summary>

- [`_internal`](#_internal)
- [`async_search`](#async_search)
- [`autoscaling`](#autoscaling)
- [`global`](#global)
- [`cat`](#cat)
- [`ccr`](#ccr)
- [`cluster`](#cluster)
- [`connector`](#connector)
- [`dangling_indices`](#dangling_indices)
- [`enrich`](#enrich)
- [`eql`](#eql)
- [`esql`](#esql)
- [`features`](#features)
- [`fleet`](#fleet)
- [`graph`](#graph)
- [`ilm`](#ilm)
- [`indices`](#indices)
- [`inference`](#inference)
- [`ingest`](#ingest)
- [`license`](#license)
- [`logstash`](#logstash)
- [`migration`](#migration)
- [`ml`](#ml)
- [`monitoring`](#monitoring)
- [`nodes`](#nodes)
- [`profiling`](#profiling)
- [`project`](#project)
- [`query_rules`](#query_rules)
- [`rollup`](#rollup)
- [`search_application`](#search_application)
- [`searchable_snapshots`](#searchable_snapshots)
- [`security`](#security)
- [`shutdown`](#shutdown)
- [`simulate`](#simulate)
- [`slm`](#slm)
- [`snapshot`](#snapshot)
- [`sql`](#sql)
- [`ssl`](#ssl)
- [`streams`](#streams)
- [`synonyms`](#synonyms)
- [`tasks`](#tasks)
- [`text_structure`](#text_structure)
- [`transform`](#transform)
- [`watcher`](#watcher)
- [`xpack`](#xpack)

</details>

## Report

:construction: 24.4% namespaces have failures, and the namespace with the most failures is [`xpack`](#xpack) with 50% failures.

### _internal

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_desired_balance` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `delete_desired_nodes` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `get_desired_balance` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `get_desired_nodes` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `prevalidate_node_removal` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `update_desired_nodes` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| **Summary** | :orange_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### async_search

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `get` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `status` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `submit` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### autoscaling

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_autoscaling_policy` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_autoscaling_capacity` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_autoscaling_policy` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_autoscaling_policy` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| **Summary** | :white_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### global

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `bulk` | :green_circle: | 558/558 | 576/576 | stable | undefined |  |
| `capabilities` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `clear_scroll` | :green_circle: | 17/17 | 17/17 | stable | undefined |  |
| `close_point_in_time` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `count` | :green_circle: | 37/37 | 37/37 | stable | undefined |  |
| `create` | :green_circle: | 24/24 | 23/23 | stable | undefined |  |
| `delete` | :green_circle: | 37/37 | 37/37 | stable | undefined |  |
| `delete_by_query` | :green_circle: | 8/8 | 7/7 | stable | undefined |  |
| `delete_by_query_rethrottle` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `delete_script` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `exists` | :green_circle: | 19/19 | 19/19 | stable | undefined |  |
| `exists_source` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `explain` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `field_caps` | :green_circle: | 84/84 | 84/84 | stable | undefined |  |
| `get` | :green_circle: | 347/347 | 344/344 | stable | undefined |  |
| `get_script` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `get_script_context` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `get_script_languages` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `get_source` | :green_circle: | 18/18 | 18/18 | stable | undefined |  |
| `health_report` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `index` | :green_circle: | 1472/1472 | 1474/1474 | stable | undefined |  |
| `info` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `knn_search` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `mget` | :green_circle: | 51/51 | 50/50 | stable | undefined |  |
| `msearch` | :green_circle: | 18/18 | 17/17 | stable | undefined |  |
| `msearch_template` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `mtermvectors` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `open_point_in_time` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `ping` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `put_script` | :green_circle: | 49/49 | 49/49 | stable | undefined |  |
| `rank_eval` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `reindex` | :red_circle: | 21/22 | 21/21 | stable | undefined |  |
| `reindex_rethrottle` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `render_search_template` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `scripts_painless_execute` | :green_circle: | 4/4 | 4/4 | experimental | undefined |  |
| `scroll` | :green_circle: | 69/69 | 20/20 | stable | undefined |  |
| `search` | :red_circle: | 2570/2640 | 2640/2640 | stable | undefined |  |
| `search_mvt` | :green_circle: | 34/34 | 0/0 | stable | undefined |  |
| `search_shards` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `search_template` | :green_circle: | 2/2 | 1/1 | stable | undefined |  |
| `terms_enum` | :green_circle: | 47/47 | 47/47 | stable | undefined |  |
| `termvectors` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `update` | :green_circle: | 49/49 | 49/49 | stable | undefined |  |
| `update_by_query` | :green_circle: | 11/11 | 10/10 | stable | undefined |  |
| `update_by_query_rethrottle` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| **Summary** | :red_circle: | 98.8% | 100% | | | |

[Back to top](#Summary)

### cat

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `aliases` | :green_circle: | 29/29 | 29/29 | stable | undefined |  |
| `allocation` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `component_templates` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `count` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `fielddata` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `health` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `help` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `indices` | :green_circle: | 34/34 | 33/33 | stable | undefined |  |
| `master` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `ml_data_frame_analytics` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `ml_datafeeds` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `ml_jobs` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `ml_trained_models` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `nodeattrs` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `nodes` | :green_circle: | 11/11 | 11/11 | stable | undefined |  |
| `pending_tasks` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `plugins` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `recovery` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `repositories` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `segments` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `shards` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `snapshots` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `tasks` | :green_circle: | 11/11 | 11/11 | experimental | undefined |  |
| `templates` | :green_circle: | 17/17 | 17/17 | stable | undefined |  |
| `thread_pool` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `transforms` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### ccr

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_auto_follow_pattern` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `follow` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `follow_info` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `follow_stats` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `forget_follower` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_auto_follow_pattern` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `pause_auto_follow_pattern` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `pause_follow` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_auto_follow_pattern` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `resume_auto_follow_pattern` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `resume_follow` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `stats` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `unfollow` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| **Summary** | :white_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### cluster

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `allocation_explain` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `delete_component_template` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_voting_config_exclusions` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `exists_component_template` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_component_template` | :green_circle: | 14/14 | 14/14 | stable | undefined |  |
| `get_settings` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `health` | :green_circle: | 214/214 | 214/214 | stable | undefined |  |
| `info` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `pending_tasks` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `post_voting_config_exclusions` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `put_component_template` | :red_circle: | 34/38 | 38/38 | stable | undefined |  |
| `put_settings` | :green_circle: | 62/62 | 61/61 | stable | undefined |  |
| `remote_info` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `reroute` | :green_circle: | 8/8 | 7/7 | stable | undefined |  |
| `state` | :green_circle: | 84/84 | 83/83 | stable | undefined |  |
| `stats` | :red_circle: | 27/27 | 0/27 | stable | undefined |  |
| **Summary** | :red_circle: | 99.2% | 94.3% | | | |

[Back to top](#Summary)

### connector

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `check_in` | :green_circle: | 3/3 | 3/3 | experimental | undefined |  |
| `delete` | :green_circle: | 29/29 | 29/29 | beta | undefined |  |
| `get` | :green_circle: | 64/64 | 64/64 | beta | undefined |  |
| `last_sync` | :green_circle: | 7/7 | 7/7 | experimental | undefined |  |
| `list` | :green_circle: | 31/31 | 31/31 | beta | undefined |  |
| `post` | :green_circle: | 7/7 | 7/7 | beta | undefined |  |
| `put` | :green_circle: | 20/20 | 20/20 | beta | undefined |  |
| `secret_delete` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `secret_get` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `secret_post` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `secret_put` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `sync_job_cancel` | :green_circle: | 3/3 | 3/3 | beta | undefined |  |
| `sync_job_check_in` | :green_circle: | 3/3 | 3/3 | experimental | undefined |  |
| `sync_job_claim` | :green_circle: | 3/3 | 3/3 | experimental | undefined |  |
| `sync_job_delete` | :green_circle: | 4/4 | 4/4 | beta | undefined |  |
| `sync_job_error` | :green_circle: | 1/1 | 1/1 | experimental | undefined |  |
| `sync_job_get` | :green_circle: | 22/22 | 22/22 | beta | undefined |  |
| `sync_job_list` | :green_circle: | 12/12 | 12/12 | beta | undefined |  |
| `sync_job_post` | :green_circle: | 50/50 | 50/50 | beta | undefined |  |
| `sync_job_update_stats` | :green_circle: | 5/5 | 5/5 | experimental | undefined |  |
| `update_active_filtering` | :green_circle: | 1/1 | 1/1 | experimental | undefined |  |
| `update_api_key_id` | :green_circle: | 4/4 | 4/4 | beta | undefined |  |
| `update_configuration` | :green_circle: | 8/8 | 8/8 | beta | undefined |  |
| `update_error` | :green_circle: | 4/4 | 4/4 | experimental | undefined |  |
| `update_features` | :green_circle: | 4/4 | 4/4 | experimental | undefined |  |
| `update_filtering` | :green_circle: | 12/12 | 12/12 | beta | undefined |  |
| `update_filtering_validation` | :green_circle: | 3/3 | 3/3 | experimental | undefined |  |
| `update_index_name` | :green_circle: | 5/5 | 5/5 | beta | undefined |  |
| `update_name` | :green_circle: | 4/4 | 4/4 | beta | undefined |  |
| `update_native` | :green_circle: | 4/4 | 4/4 | beta | undefined |  |
| `update_pipeline` | :green_circle: | 3/3 | 3/3 | beta | undefined |  |
| `update_scheduling` | :green_circle: | 3/3 | 3/3 | beta | undefined |  |
| `update_service_type` | :green_circle: | 2/2 | 2/2 | beta | undefined |  |
| `update_status` | :green_circle: | 3/3 | 3/3 | experimental | undefined |  |
| **Summary** | :orange_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### dangling_indices

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_dangling_index` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `import_dangling_index` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `list_dangling_indices` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| **Summary** | :white_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### enrich

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_policy` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `execute_policy` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `get_policy` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `put_policy` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `stats` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### eql

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get_status` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `search` | :green_circle: | 40/40 | 40/40 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### esql

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `async_query` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `async_query_delete` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `async_query_get` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `async_query_stop` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_query` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| `list_queries` | :green_circle: | 1/1 | 0/0 | experimental | undefined |  |
| `query` | :green_circle: | 349/349 | 0/0 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 0% | | | |

[Back to top](#Summary)

### features

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `get_features` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `reset_features` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### fleet

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_secret` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `get_secret` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `global_checkpoints` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `msearch` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| `post_secret` | :orange_circle: | Missing type | Missing type | experimental | undefined |  |
| `search` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| **Summary** | :orange_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### graph

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `explore` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### ilm

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_lifecycle` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `explain_lifecycle` | :red_circle: | 5/5 | 4/5 | stable | undefined |  |
| `get_lifecycle` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `get_status` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `migrate_to_data_tiers` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `move_to_step` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_lifecycle` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `remove_policy` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `retry` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `start` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `stop` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| **Summary** | :red_circle: | 100% | 97.1% | | | |

[Back to top](#Summary)

### indices

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `add_block` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `analyze` | :green_circle: | 246/246 | 246/246 | stable | undefined |  |
| `cancel_migrate_reindex` | :green_circle: | 2/2 | 2/2 | experimental | undefined |  |
| `clear_cache` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `clone` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `close` | :green_circle: | 50/50 | 50/50 | stable | undefined |  |
| `create` | :red_circle: | 1362/1402 | 1402/1402 | stable | undefined |  |
| `create_data_stream` | :green_circle: | 121/121 | 121/121 | stable | undefined |  |
| `create_from` | :green_circle: | 4/4 | 4/4 | experimental | undefined |  |
| `data_streams_stats` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `delete` | :green_circle: | 119/119 | 119/119 | stable | undefined |  |
| `delete_alias` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `delete_data_lifecycle` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_data_stream` | :green_circle: | 96/96 | 96/96 | stable | undefined |  |
| `delete_data_stream_options` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `delete_index_template` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `delete_template` | :green_circle: | 9/9 | 9/9 | stable | undefined | deprecated |
| `disk_usage` | :green_circle: | 6/6 | 6/6 | experimental | undefined |  |
| `downsample` | :green_circle: | 9/9 | 9/9 | experimental | undefined |  |
| `exists` | :green_circle: | 44/44 | 44/44 | stable | undefined |  |
| `exists_alias` | :green_circle: | 37/37 | 37/37 | stable | undefined |  |
| `exists_index_template` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `exists_template` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `explain_data_lifecycle` | :red_circle: | 3/3 | 0/3 | stable | undefined |  |
| `field_usage_stats` | :green_circle: | 5/5 | 5/5 | experimental | undefined |  |
| `flush` | :green_circle: | 52/52 | 52/52 | stable | undefined |  |
| `forcemerge` | :green_circle: | 14/14 | 14/14 | stable | undefined |  |
| `get` | :green_circle: | 66/66 | 66/66 | stable | undefined |  |
| `get_alias` | :green_circle: | 75/75 | 75/75 | stable | undefined |  |
| `get_data_lifecycle` | :red_circle: | 14/14 | 1/14 | stable | undefined |  |
| `get_data_lifecycle_stats` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_data_stream` | :red_circle: | 124/124 | 77/124 | stable | undefined |  |
| `get_data_stream_mappings` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get_data_stream_options` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `get_data_stream_settings` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `get_field_mapping` | :green_circle: | 30/30 | 30/30 | stable | undefined |  |
| `get_index_template` | :green_circle: | 23/23 | 23/23 | stable | undefined |  |
| `get_mapping` | :red_circle: | 228/228 | 215/228 | stable | undefined |  |
| `get_migrate_reindex_status` | :green_circle: | 1/1 | 1/1 | experimental | undefined |  |
| `get_settings` | :red_circle: | 85/85 | 66/85 | stable | undefined |  |
| `get_template` | :green_circle: | 32/32 | 32/32 | stable | undefined | deprecated |
| `migrate_reindex` | :green_circle: | 2/2 | 2/2 | experimental | undefined |  |
| `migrate_to_data_stream` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `modify_data_stream` | :red_circle: | 3/7 | 7/7 | stable | undefined |  |
| `open` | :green_circle: | 21/21 | 21/21 | stable | undefined |  |
| `promote_data_stream` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_alias` | :red_circle: | 64/64 | 21/64 | stable | undefined |  |
| `put_data_lifecycle` | :red_circle: | 5/6 | 6/6 | stable | undefined |  |
| `put_data_stream_mappings` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `put_data_stream_options` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `put_data_stream_settings` | :red_circle: | 8/10 | 0/10 | stable | undefined |  |
| `put_index_template` | :red_circle: | 130/154 | 154/154 | stable | undefined |  |
| `put_mapping` | :red_circle: | 142/150 | 153/153 | stable | undefined |  |
| `put_settings` | :red_circle: | 56/58 | 58/58 | stable | undefined |  |
| `put_template` | :red_circle: | 45/46 | 46/46 | stable | undefined | deprecated |
| `recovery` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `refresh` | :green_circle: | 328/328 | 328/328 | stable | undefined |  |
| `reload_search_analyzers` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `remove_block` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `resolve_cluster` | :green_circle: | 13/13 | 13/13 | stable | undefined |  |
| `resolve_index` | :green_circle: | 13/13 | 13/13 | stable | undefined |  |
| `rollover` | :red_circle: | 56/56 | 2/56 | stable | undefined |  |
| `segments` | :red_circle: | 6/6 | 5/6 | stable | undefined |  |
| `shard_stores` | :red_circle: | 6/6 | 5/6 | stable | undefined |  |
| `shrink` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `simulate_index_template` | :red_circle: | 10/10 | 6/10 | stable | undefined |  |
| `simulate_template` | :red_circle: | 5/5 | 4/5 | stable | undefined |  |
| `split` | :green_circle: | 11/11 | 11/11 | stable | undefined |  |
| `stats` | :red_circle: | 125/125 | 36/124 | stable | undefined |  |
| `update_aliases` | :red_circle: | 33/33 | 7/33 | stable | undefined |  |
| `validate_query` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| **Summary** | :red_circle: | 98% | 92.2% | | | |

[Back to top](#Summary)

### inference

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `chat_completion_unified` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `completion` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `delete` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `inference` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `put_ai21` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_alibabacloud` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_amazonbedrock` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_amazonsagemaker` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_anthropic` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_azureaistudio` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_azureopenai` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_cohere` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_custom` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_deepseek` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_elasticsearch` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_elser` | :white_circle: | Missing test | Missing test | stable | undefined | deprecated |
| `put_googleaistudio` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_googlevertexai` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_hugging_face` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_jinaai` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_llama` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_mistral` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_openai` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_voyageai` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_watsonx` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `rerank` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `sparse_embedding` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `stream_completion` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `text_embedding` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `update` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### ingest

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_geoip_database` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `delete_ip_location_database` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `delete_pipeline` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `geo_ip_stats` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `get_geoip_database` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `get_ip_location_database` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `get_pipeline` | :green_circle: | 23/23 | 23/23 | stable | undefined |  |
| `processor_grok` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `put_geoip_database` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `put_ip_location_database` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `put_pipeline` | :green_circle: | 78/78 | 78/78 | stable | undefined |  |
| `simulate` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### license

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `get_basic_status` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get_trial_status` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `post` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `post_start_basic` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `post_start_trial` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### logstash

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_pipeline` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_pipeline` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_pipeline` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| **Summary** | :white_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### migration

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `deprecations` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `get_feature_upgrade_status` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `post_feature_upgrade` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### ml

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `clear_trained_model_deployment_cache` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `close_job` | :green_circle: | 26/26 | 26/26 | stable | undefined |  |
| `delete_calendar` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `delete_calendar_event` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `delete_calendar_job` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_data_frame_analytics` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_datafeed` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_expired_data` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `delete_filter` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `delete_forecast` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_job` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `delete_model_snapshot` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `delete_trained_model` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `delete_trained_model_alias` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `estimate_model_memory` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `evaluate_data_frame` | :green_circle: | 22/22 | 22/22 | stable | undefined |  |
| `explain_data_frame_analytics` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `flush_job` | :green_circle: | 6/6 | 6/6 | stable | undefined | deprecated |
| `forecast` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_buckets` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `get_calendar_events` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `get_calendars` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `get_categories` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `get_data_frame_analytics` | :green_circle: | 17/17 | 17/17 | stable | undefined |  |
| `get_data_frame_analytics_stats` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `get_datafeed_stats` | :green_circle: | 25/25 | 25/25 | stable | undefined |  |
| `get_datafeeds` | :green_circle: | 18/18 | 18/18 | stable | undefined |  |
| `get_filters` | :green_circle: | 11/11 | 11/11 | stable | undefined |  |
| `get_influencers` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `get_job_stats` | :green_circle: | 30/30 | 30/30 | stable | undefined |  |
| `get_jobs` | :green_circle: | 29/29 | 29/29 | stable | undefined |  |
| `get_memory_stats` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `get_model_snapshot_upgrade_stats` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get_model_snapshots` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `get_overall_buckets` | :green_circle: | 15/15 | 15/15 | stable | undefined |  |
| `get_records` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `get_trained_models` | :green_circle: | 36/36 | 36/36 | stable | undefined |  |
| `get_trained_models_stats` | :green_circle: | 17/17 | 17/17 | stable | undefined |  |
| `infer_trained_model` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `info` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `open_job` | :green_circle: | 38/38 | 38/38 | stable | undefined |  |
| `post_calendar_events` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `post_data` | :green_circle: | 9/9 | 9/9 | stable | undefined | deprecated |
| `preview_data_frame_analytics` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `preview_datafeed` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `put_calendar` | :green_circle: | 22/22 | 22/22 | stable | undefined |  |
| `put_calendar_job` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `put_data_frame_analytics` | :green_circle: | 33/33 | 33/33 | stable | undefined |  |
| `put_datafeed` | :green_circle: | 30/30 | 30/30 | stable | undefined |  |
| `put_filter` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `put_job` | :green_circle: | 65/65 | 65/65 | stable | undefined |  |
| `put_trained_model` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `put_trained_model_alias` | :green_circle: | 13/13 | 13/13 | stable | undefined |  |
| `put_trained_model_definition_part` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `put_trained_model_vocabulary` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `reset_job` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `revert_model_snapshot` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `set_upgrade_mode` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `start_data_frame_analytics` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `start_datafeed` | :green_circle: | 19/19 | 19/19 | stable | undefined |  |
| `start_trained_model_deployment` | :green_circle: | 14/14 | 14/14 | stable | undefined |  |
| `stop_data_frame_analytics` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `stop_datafeed` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `stop_trained_model_deployment` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `update_data_frame_analytics` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `update_datafeed` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `update_filter` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `update_job` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `update_model_snapshot` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `update_trained_model_deployment` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `upgrade_job_snapshot` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `validate` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `validate_detector` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### monitoring

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `bulk` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### nodes

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `clear_repositories_metering_archive` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| `get_repositories_metering_info` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| `hot_threads` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `info` | :green_circle: | 116/116 | 116/116 | stable | undefined |  |
| `reload_secure_settings` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `stats` | :red_circle: | 58/58 | 21/58 | stable | undefined |  |
| `usage` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| **Summary** | :red_circle: | 100% | 79.7% | | | |

[Back to top](#Summary)

### profiling

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `flamegraph` | :orange_circle: | Missing type | Missing type | stable | undefined |  |
| `stacktraces` | :orange_circle: | Missing type | Missing type | stable | undefined |  |
| `status` | :orange_circle: | Missing type | Missing type | stable | undefined |  |
| `topn_functions` | :orange_circle: | Missing type | Missing type | stable | undefined |  |
| **Summary** | :orange_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### project

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `tags` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| **Summary** | :white_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### query_rules

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_rule` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `delete_ruleset` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `get_rule` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `get_ruleset` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `list_rulesets` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `put_rule` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `put_ruleset` | :green_circle: | 17/17 | 17/17 | stable | undefined |  |
| `test` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### rollup

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_job` | :green_circle: | 3/3 | 3/3 | experimental | undefined | deprecated |
| `get_jobs` | :green_circle: | 10/10 | 10/10 | experimental | undefined | deprecated |
| `get_rollup_caps` | :green_circle: | 3/3 | 3/3 | experimental | undefined | deprecated |
| `get_rollup_index_caps` | :green_circle: | 7/7 | 7/7 | experimental | undefined | deprecated |
| `put_job` | :green_circle: | 22/22 | 22/22 | experimental | undefined | deprecated |
| `rollup_search` | :green_circle: | 18/18 | 18/18 | experimental | undefined | deprecated |
| `start_job` | :green_circle: | 6/6 | 6/6 | experimental | undefined | deprecated |
| `stop_job` | :green_circle: | 5/5 | 5/5 | experimental | undefined | deprecated |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### search_application

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete` | :green_circle: | 7/7 | 7/7 | beta | undefined |  |
| `delete_behavioral_analytics` | :green_circle: | 3/3 | 3/3 | experimental | undefined | deprecated |
| `get` | :red_circle: | 10/10 | 7/10 | beta | undefined |  |
| `get_behavioral_analytics` | :red_circle: | 2/5 | 5/5 | experimental | undefined | deprecated |
| `list` | :red_circle: | 7/7 | 2/7 | beta | undefined |  |
| `post_behavioral_analytics_event` | :green_circle: | 18/18 | 18/18 | experimental | undefined | deprecated |
| `put` | :red_circle: | 6/10 | 10/10 | beta | undefined |  |
| `put_behavioral_analytics` | :green_circle: | 3/3 | 3/3 | experimental | undefined | deprecated |
| `render_query` | :green_circle: | 7/7 | 7/7 | experimental | undefined |  |
| `search` | :green_circle: | 16/16 | 16/16 | beta | undefined |  |
| **Summary** | :red_circle: | 91.9% | 90.7% | | | |

[Back to top](#Summary)

### searchable_snapshots

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `cache_stats` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| `clear_cache` | :green_circle: | 1/1 | 1/1 | experimental | undefined |  |
| `mount` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `stats` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### security

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `activate_user_profile` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `authenticate` | :red_circle: | 30/30 | 25/30 | stable | undefined |  |
| `bulk_delete_role` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `bulk_put_role` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `bulk_update_api_keys` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `change_password` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `clear_api_key_cache` | :green_circle: | 13/13 | 13/13 | stable | undefined |  |
| `clear_cached_privileges` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `clear_cached_realms` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `clear_cached_roles` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `clear_cached_service_tokens` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `create_api_key` | :green_circle: | 68/68 | 59/59 | stable | undefined |  |
| `create_cross_cluster_api_key` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `create_service_token` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delegate_pki` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `delete_privileges` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `delete_role` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `delete_role_mapping` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `delete_service_token` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `delete_user` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `disable_user` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `disable_user_profile` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `enable_user` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `enable_user_profile` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `enroll_kibana` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `enroll_node` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_api_key` | :green_circle: | 26/26 | 26/26 | stable | undefined |  |
| `get_builtin_privileges` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `get_privileges` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `get_role` | :green_circle: | 24/24 | 24/24 | stable | undefined |  |
| `get_role_mapping` | :red_circle: | 18/18 | 10/18 | stable | undefined |  |
| `get_service_accounts` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_service_credentials` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `get_settings` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `get_stats` | :orange_circle: | Missing type | Missing type | stable | undefined |  |
| `get_token` | :green_circle: | 25/25 | 24/24 | stable | undefined |  |
| `get_user` | :green_circle: | 25/25 | 25/25 | stable | undefined |  |
| `get_user_privileges` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `get_user_profile` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `grant_api_key` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `has_privileges` | :green_circle: | 24/24 | 24/24 | stable | undefined |  |
| `has_privileges_user_profile` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `invalidate_api_key` | :green_circle: | 12/12 | 12/12 | stable | undefined |  |
| `invalidate_token` | :green_circle: | 11/11 | 11/11 | stable | undefined |  |
| `oidc_authenticate` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `oidc_logout` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `oidc_prepare_authentication` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_privileges` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `put_role` | :green_circle: | 39/39 | 38/38 | stable | undefined |  |
| `put_role_mapping` | :red_circle: | 2/11 | 11/11 | stable | undefined |  |
| `put_user` | :green_circle: | 48/48 | 47/47 | stable | undefined |  |
| `query_api_keys` | :green_circle: | 14/14 | 14/14 | stable | undefined |  |
| `query_role` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `query_user` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `saml_authenticate` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `saml_complete_logout` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `saml_invalidate` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `saml_logout` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `saml_prepare_authentication` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `saml_service_provider_metadata` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `suggest_user_profiles` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `update_api_key` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `update_cross_cluster_api_key` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `update_settings` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `update_user_profile_data` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| **Summary** | :red_circle: | 98.3% | 97.5% | | | |

[Back to top](#Summary)

### shutdown

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_node` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_node` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `put_node` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| **Summary** | :white_circle: | 0% | 0% | | | |

[Back to top](#Summary)

### simulate

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `ingest` | :green_circle: | 11/11 | 11/11 | experimental | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### slm

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_lifecycle` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `execute_lifecycle` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `execute_retention` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `get_lifecycle` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `get_stats` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `get_status` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `put_lifecycle` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `start` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `stop` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### snapshot

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `cleanup_repository` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `clone` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `create` | :green_circle: | 30/30 | 30/30 | stable | undefined |  |
| `create_repository` | :red_circle: | 24/29 | 29/29 | stable | undefined |  |
| `delete` | :green_circle: | 24/24 | 24/24 | stable | undefined |  |
| `delete_repository` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `get` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `get_repository` | :red_circle: | 19/19 | 7/19 | stable | undefined |  |
| `repository_analyze` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `repository_verify_integrity` | :white_circle: | Missing test | Missing test | experimental | undefined |  |
| `restore` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `status` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `verify_repository` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| **Summary** | :red_circle: | 96.6% | 91.7% | | | |

[Back to top](#Summary)

### sql

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `clear_cursor` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `delete_async` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_async` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `get_async_status` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `query` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `translate` | :red_circle: | 1/1 | 0/1 | stable | undefined |  |
| **Summary** | :red_circle: | 100% | 83.3% | | | |

[Back to top](#Summary)

### ssl

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `certificates` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### streams

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `logs_disable` | :green_circle: | 3/3 | 3/3 | experimental | undefined |  |
| `logs_enable` | :green_circle: | 11/11 | 11/11 | experimental | undefined |  |
| `status` | :green_circle: | 10/10 | 10/10 | experimental | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### synonyms

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_synonym` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `delete_synonym_rule` | :green_circle: | 8/8 | 8/8 | stable | undefined |  |
| `get_synonym` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `get_synonym_rule` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `get_synonyms_sets` | :green_circle: | 7/7 | 7/7 | stable | undefined |  |
| `put_synonym` | :green_circle: | 32/32 | 32/32 | stable | undefined |  |
| `put_synonym_rule` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### tasks

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `cancel` | :green_circle: | 2/2 | 2/2 | experimental | undefined |  |
| `get` | :green_circle: | 10/10 | 10/10 | experimental | undefined |  |
| `list` | :green_circle: | 9/9 | 9/9 | experimental | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### text_structure

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `find_field_structure` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `find_message_structure` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `find_structure` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `test_grok_pattern` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| **Summary** | :green_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### transform

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `delete_transform` | :green_circle: | 10/10 | 10/10 | stable | undefined |  |
| `get_node_stats` | :orange_circle: | Missing type | Missing type | stable | undefined |  |
| `get_transform` | :green_circle: | 26/26 | 26/26 | stable | undefined |  |
| `get_transform_stats` | :green_circle: | 34/34 | 34/34 | stable | undefined |  |
| `preview_transform` | :green_circle: | 21/21 | 21/21 | stable | undefined |  |
| `put_transform` | :green_circle: | 28/28 | 28/28 | stable | undefined |  |
| `reset_transform` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `schedule_now_transform` | :green_circle: | 3/3 | 3/3 | stable | undefined |  |
| `set_upgrade_mode` | :white_circle: | Missing test | Missing test | stable | undefined |  |
| `start_transform` | :green_circle: | 29/29 | 29/29 | stable | undefined |  |
| `stop_transform` | :green_circle: | 16/16 | 16/16 | stable | undefined |  |
| `update_transform` | :green_circle: | 14/14 | 14/14 | stable | undefined |  |
| `upgrade_transforms` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| **Summary** | :orange_circle: | 100% | 100% | | | |

[Back to top](#Summary)

### watcher

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `ack_watch` | :green_circle: | 5/5 | 5/5 | stable | undefined |  |
| `activate_watch` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `deactivate_watch` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `delete_watch` | :green_circle: | 9/9 | 9/9 | stable | undefined |  |
| `execute_watch` | :red_circle: | 34/55 | 1/55 | stable | undefined |  |
| `get_settings` | :green_circle: | 4/4 | 4/4 | stable | undefined |  |
| `get_watch` | :red_circle: | 37/37 | 34/37 | stable | undefined |  |
| `put_watch` | :red_circle: | 46/53 | 53/53 | stable | undefined |  |
| `query_watches` | :red_circle: | 1/1 | 0/1 | stable | undefined |  |
| `start` | :green_circle: | 2/2 | 2/2 | stable | undefined |  |
| `stats` | :green_circle: | 6/6 | 6/6 | stable | undefined |  |
| `stop` | :green_circle: | 1/1 | 1/1 | stable | undefined |  |
| `update_settings` | :red_circle: | 0/3 | 3/3 | stable | undefined |  |
| **Summary** | :red_circle: | 82.8% | 67.8% | | | |

[Back to top](#Summary)

### xpack

| API | Status | Request | Response | Stability | Visibility | Meta |
| --- | --- | --- | --- | --- | --- | --- |
| `info` | :green_circle: | 8/8 | 4/4 | stable | undefined |  |
| `usage` | :red_circle: | 45/45 | 2/41 | stable | undefined |  |
| **Summary** | :red_circle: | 100% | 13.3% | | | |

[Back to top](#Summary)

