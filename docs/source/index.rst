<!DOCTYPE html>
<html class="writer-html5" lang="en" data-content_root="./">
<head>
  <meta charset="utf-8" /><meta name="viewport" content="width=device-width, initial-scale=1" />

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>IA-SDK Python documentation! &mdash; IA-SDK-Python 0.4.24 documentation</title>
      <link rel="stylesheet" type="text/css" href="_static/pygments.css?v=80d5e7a1" />
      <link rel="stylesheet" type="text/css" href="_static/css/theme.css?v=19f00094" />
      <link rel="stylesheet" type="text/css" href="_static/copybutton.css?v=76b2166b" />
      <link rel="stylesheet" type="text/css" href="_static/sphinxcontrib-httpexample.css" />

  
  <!--[if lt IE 9]>
    <script src="_static/js/html5shiv.min.js"></script>
  <![endif]-->
  
        <script src="_static/jquery.js?v=5d32c60e"></script>
        <script src="_static/_sphinx_javascript_frameworks_compat.js?v=2cd50e6c"></script>
        <script src="_static/documentation_options.js?v=b2057829"></script>
        <script src="_static/doctools.js?v=888ff710"></script>
        <script src="_static/sphinx_highlight.js?v=dc90522c"></script>
        <script src="_static/clipboard.min.js?v=a7894cd8"></script>
        <script src="_static/copybutton.js?v=f281be69"></script>
        <script src="_static/sphinxcontrib-httpexample.js"></script>
        <script crossorigin="anonymous" integrity="sha256-Ae2Vz/4ePdIu6ZyI/5ZGsYnb+m0JlOmKPjt6XZ9JJkA=" src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.3.4/require.min.js"></script>
    <script src="_static/js/theme.js"></script>
    <link rel="index" title="Index" href="genindex.html" />
    <link rel="search" title="Search" href="search.html" />
    <link rel="next" title="GAIuS Data Format (GDF)" href="GDF.html" /> 
</head>

<body class="wy-body-for-nav"> 
  <div class="wy-grid-for-nav">
    <nav data-toggle="wy-nav-shift" class="wy-nav-side">
      <div class="wy-side-scroll">
        <div class="wy-side-nav-search" >

          
          
          <a href="#" class="icon icon-home">
            IA-SDK-Python
              <img src="_static/ia_with_text_white.svg" class="logo" alt="Logo"/>
          </a>
              <div class="version">
                v0.4.24
              </div>
<div role="search">
  <form id="rtd-search-form" class="wy-form" action="search.html" method="get">
    <input type="text" name="q" placeholder="Search docs" aria-label="Search docs" />
    <input type="hidden" name="check_keywords" value="yes" />
    <input type="hidden" name="area" value="default" />
  </form>
</div>
        </div><div class="wy-menu wy-menu-vertical" data-spy="affix" role="navigation" aria-label="Navigation menu">
              <p class="caption" role="heading"><span class="caption-text">Contents:</span></p>
<ul>
<li class="toctree-l1"><a class="reference internal" href="GDF.html">GAIuS Data Format (GDF)</a><ul>
<li class="toctree-l2"><a class="reference internal" href="GDF.html#fields">Fields</a><ul>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#strings">strings</a></li>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#vectors">vectors</a></li>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#emotives">emotives</a></li>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#metadata">metadata</a></li>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#path">path</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="GDF.html#example-conversions">Example Conversions</a><ul>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#csv-to-gdf">CSV to GDF</a></li>
<li class="toctree-l3"><a class="reference internal" href="GDF.html#image-to-gdf">Image to GDF</a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="Tutorials.html">Tutorials</a><ul>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Quick%20Start%20-%20Hello%2C%20World%21.html">Quick Start: Hello, World!</a><ul>
<li class="toctree-l3"><a class="reference internal" href="tutorial_segments/Quick%20Start%20-%20Hello%2C%20World%21.html#Four-API-Calls">Four API Calls</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Genome%20Introduction.html">Create a Genome Topology for your Agent</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Creation.html">Deploy an Agent</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Creation.html#Connect-to-Your-Agent">Connect to Your Agent</a><ul>
<li class="toctree-l3"><a class="reference internal" href="tutorial_segments/Agent%20Creation.html#Use-the-SDK's-AgentClient">Use the SDK’s AgentClient</a></li>
<li class="toctree-l3"><a class="reference internal" href="tutorial_segments/Agent%20Creation.html#Or,-roll-your-own-connections">Or, roll your own connections</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html">Interact with your Agent using String Data</a><ul>
<li class="toctree-l3"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Data-Preparation">Data Preparation</a></li>
<li class="toctree-l3"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Observing-data">Observing data</a><ul>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Observe-1st-Sequence">Observe 1st Sequence</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Learn-1st-Sequence">Learn 1st Sequence</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Observe-2nd-Sequence">Observe 2nd Sequence</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Learn-2nd-Sequence">Learn 2nd Sequence</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Show-Agent-Status">Show Agent Status</a></li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Get-Predictions">Get Predictions</a><ul>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Observe-1st-event-in-New-Sequence">Observe 1st event in New Sequence</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#id1">Get Predictions</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#Observe-2nd-event-in-New-Sequence">Observe 2nd event in New Sequence</a></li>
<li class="toctree-l4"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html#id2">Get Predictions</a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Emotives.html">An Emotional Machine: Emotives and Mood</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="API.html">API Reference</a><ul>
<li class="toctree-l2"><a class="reference internal" href="AgentClient.html">AgentClient</a><ul>
<li class="toctree-l3"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient"><code class="docutils literal notranslate"><span class="pre">AgentClient</span></code></a><ul>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.__init__"><code class="docutils literal notranslate"><span class="pre">AgentClient.__init__()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.add_blacklisted_symbols"><code class="docutils literal notranslate"><span class="pre">AgentClient.add_blacklisted_symbols()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.add_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.add_model()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.change_genes"><code class="docutils literal notranslate"><span class="pre">AgentClient.change_genes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.clear_all_memory"><code class="docutils literal notranslate"><span class="pre">AgentClient.clear_all_memory()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.clear_snapshots"><code class="docutils literal notranslate"><span class="pre">AgentClient.clear_snapshots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.clear_target_class"><code class="docutils literal notranslate"><span class="pre">AgentClient.clear_target_class()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.clear_wm"><code class="docutils literal notranslate"><span class="pre">AgentClient.clear_wm()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.connect"><code class="docutils literal notranslate"><span class="pre">AgentClient.connect()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.delete_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.delete_model()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_all_genes"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_all_genes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_cluster_info"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_cluster_info()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_cognition_data"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_cognition_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_gene"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_gene()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_hypotheses"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_hypotheses()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_info"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_info()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_interface_node_config"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_interface_node_config()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_kbs_as_json"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_kbs_as_json()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_model()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_models_with_patterns"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_models_with_patterns()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_models_with_symbols"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_models_with_symbols()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_name"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_name()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_percept_data"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_percept_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_prediction_ensemble_for_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_prediction_ensemble_for_model()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_predictions"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_predictions()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_successor_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_successor_model()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_symbol"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_symbol()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_time"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_time()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_vector"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_vector()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.get_wm"><code class="docutils literal notranslate"><span class="pre">AgentClient.get_wm()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.increment_recall_threshold"><code class="docutils literal notranslate"><span class="pre">AgentClient.increment_recall_threshold()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.inject_genome"><code class="docutils literal notranslate"><span class="pre">AgentClient.inject_genome()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.investigate"><code class="docutils literal notranslate"><span class="pre">AgentClient.investigate()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.investigate_record"><code class="docutils literal notranslate"><span class="pre">AgentClient.investigate_record()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.learn"><code class="docutils literal notranslate"><span class="pre">AgentClient.learn()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.list_blacklisted_symbols"><code class="docutils literal notranslate"><span class="pre">AgentClient.list_blacklisted_symbols()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.load_kbs_from_json"><code class="docutils literal notranslate"><span class="pre">AgentClient.load_kbs_from_json()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.load_kbs_from_json_iter"><code class="docutils literal notranslate"><span class="pre">AgentClient.load_kbs_from_json_iter()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.observe"><code class="docutils literal notranslate"><span class="pre">AgentClient.observe()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.observe_classification"><code class="docutils literal notranslate"><span class="pre">AgentClient.observe_classification()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.ping"><code class="docutils literal notranslate"><span class="pre">AgentClient.ping()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.receive_unique_ids"><code class="docutils literal notranslate"><span class="pre">AgentClient.receive_unique_ids()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.remove_blacklisted_symbols"><code class="docutils literal notranslate"><span class="pre">AgentClient.remove_blacklisted_symbols()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.remove_patterns_from_system"><code class="docutils literal notranslate"><span class="pre">AgentClient.remove_patterns_from_system()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.remove_symbols_from_system"><code class="docutils literal notranslate"><span class="pre">AgentClient.remove_symbols_from_system()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.resolve_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.resolve_model()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.set_hypotheses"><code class="docutils literal notranslate"><span class="pre">AgentClient.set_hypotheses()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.set_ingress_nodes"><code class="docutils literal notranslate"><span class="pre">AgentClient.set_ingress_nodes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.set_query_nodes"><code class="docutils literal notranslate"><span class="pre">AgentClient.set_query_nodes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.set_summarize_for_single_node"><code class="docutils literal notranslate"><span class="pre">AgentClient.set_summarize_for_single_node()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.set_target_class"><code class="docutils literal notranslate"><span class="pre">AgentClient.set_target_class()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.set_timeout"><code class="docutils literal notranslate"><span class="pre">AgentClient.set_timeout()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.show_status"><code class="docutils literal notranslate"><span class="pre">AgentClient.show_status()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.start_autolearning"><code class="docutils literal notranslate"><span class="pre">AgentClient.start_autolearning()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.start_predicting"><code class="docutils literal notranslate"><span class="pre">AgentClient.start_predicting()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.start_sleeping"><code class="docutils literal notranslate"><span class="pre">AgentClient.start_sleeping()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.stop_autolearning"><code class="docutils literal notranslate"><span class="pre">AgentClient.stop_autolearning()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.stop_predicting"><code class="docutils literal notranslate"><span class="pre">AgentClient.stop_predicting()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.stop_sleeping"><code class="docutils literal notranslate"><span class="pre">AgentClient.stop_sleeping()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.switch_to_clusters"><code class="docutils literal notranslate"><span class="pre">AgentClient.switch_to_clusters()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="AgentClient.html#ia.gaius.agent_client.AgentClient.update_model"><code class="docutils literal notranslate"><span class="pre">AgentClient.update_model()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="ThinkfluxClient.html">Thinkflux Client</a><ul>
<li class="toctree-l3"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient"><code class="docutils literal notranslate"><span class="pre">TFClient</span></code></a><ul>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.__init__"><code class="docutils literal notranslate"><span class="pre">TFClient.__init__()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.add_interface_nodes"><code class="docutils literal notranslate"><span class="pre">TFClient.add_interface_nodes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.add_schema_symbol_information"><code class="docutils literal notranslate"><span class="pre">TFClient.add_schema_symbol_information()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.bootstrap_concepts"><code class="docutils literal notranslate"><span class="pre">TFClient.bootstrap_concepts()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.clear_all_emotives"><code class="docutils literal notranslate"><span class="pre">TFClient.clear_all_emotives()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.clear_all_kbs"><code class="docutils literal notranslate"><span class="pre">TFClient.clear_all_kbs()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.clear_concepts_and_instances"><code class="docutils literal notranslate"><span class="pre">TFClient.clear_concepts_and_instances()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.clear_wm"><code class="docutils literal notranslate"><span class="pre">TFClient.clear_wm()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.delete_interface_nodes"><code class="docutils literal notranslate"><span class="pre">TFClient.delete_interface_nodes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.dreamer"><code class="docutils literal notranslate"><span class="pre">TFClient.dreamer()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.evaluate_world"><code class="docutils literal notranslate"><span class="pre">TFClient.evaluate_world()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_concept"><code class="docutils literal notranslate"><span class="pre">TFClient.get_concept()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_concepts"><code class="docutils literal notranslate"><span class="pre">TFClient.get_concepts()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_instances"><code class="docutils literal notranslate"><span class="pre">TFClient.get_instances()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_model_association_networks"><code class="docutils literal notranslate"><span class="pre">TFClient.get_model_association_networks()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_plan"><code class="docutils literal notranslate"><span class="pre">TFClient.get_plan()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_rules_kb"><code class="docutils literal notranslate"><span class="pre">TFClient.get_rules_kb()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.get_symbolic_goal"><code class="docutils literal notranslate"><span class="pre">TFClient.get_symbolic_goal()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.investigate"><code class="docutils literal notranslate"><span class="pre">TFClient.investigate()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.list_interface_nodes"><code class="docutils literal notranslate"><span class="pre">TFClient.list_interface_nodes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.load_schema_base"><code class="docutils literal notranslate"><span class="pre">TFClient.load_schema_base()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.observe"><code class="docutils literal notranslate"><span class="pre">TFClient.observe()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.ping"><code class="docutils literal notranslate"><span class="pre">TFClient.ping()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.set_rules_kb"><code class="docutils literal notranslate"><span class="pre">TFClient.set_rules_kb()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.set_symbolic_goal"><code class="docutils literal notranslate"><span class="pre">TFClient.set_symbolic_goal()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.set_verify"><code class="docutils literal notranslate"><span class="pre">TFClient.set_verify()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.show_status"><code class="docutils literal notranslate"><span class="pre">TFClient.show_status()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.timer"><code class="docutils literal notranslate"><span class="pre">TFClient.timer()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="ThinkfluxClient.html#ia.gaius.thinkflux_client.TFClient.update_schema"><code class="docutils literal notranslate"><span class="pre">TFClient.update_schema()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="comcom/COMCOMClient.html">COMCOMClient</a><ul>
<li class="toctree-l3"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient"><code class="docutils literal notranslate"><span class="pre">COMCOMClient</span></code></a><ul>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.__init__"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.__init__()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.add_function_to_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.add_function_to_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.call_agent_command"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.call_agent_command()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_agents"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_agents()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_outputslot_command_queue"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_outputslot_command_queue()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.comcom_to_cytoscape"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.comcom_to_cytoscape()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect_to_agent"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect_to_agent()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.create_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.create_pipeline()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.delete_function_from_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.delete_function_from_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.delete_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.delete_pipeline()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.desynchronize_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.desynchronize_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.disconnect_agent"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.disconnect_agent()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.disconnect_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.disconnect_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.disconnect_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.disconnect_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_agent_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_agent_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_config_as_json"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_config_as_json()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_dds_message_types"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_dds_message_types()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_debug_topic_data_single"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_debug_topic_data_single()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_debug_topic_data_stream"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_debug_topic_data_stream()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_input_slot_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_input_slot_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_output_slot_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_output_slot_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_pipeline_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_pipeline_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.input_slot_to_cytoscape"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.input_slot_to_cytoscape()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_agent_connections"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_agent_connections()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_output_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_output_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_pipelines"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_pipelines()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_preprocessing_functions"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_preprocessing_functions()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.load_comcom_config"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.load_comcom_config()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.modify_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.modify_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.modify_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.modify_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.modify_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.modify_pipeline()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.pipeline_to_cytoscape"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.pipeline_to_cytoscape()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.query_db"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.query_db()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.query_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.query_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.synchronize_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.synchronize_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.toggle_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.toggle_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.toggle_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.toggle_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.visualize_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.visualize_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.visualize_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.visualize_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.visualize_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.visualize_pipeline()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="Genome.html">Genome</a><ul>
<li class="toctree-l3"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome"><code class="docutils literal notranslate"><span class="pre">Genome</span></code></a><ul>
<li class="toctree-l4"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome.__init__"><code class="docutils literal notranslate"><span class="pre">Genome.__init__()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome.change_genes"><code class="docutils literal notranslate"><span class="pre">Genome.change_genes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome.display"><code class="docutils literal notranslate"><span class="pre">Genome.display()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome.get_manipulative_map"><code class="docutils literal notranslate"><span class="pre">Genome.get_manipulative_map()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome.get_nodes"><code class="docutils literal notranslate"><span class="pre">Genome.get_nodes()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="Genome.html#ia.gaius.genome_info.Genome.get_primitive_map"><code class="docutils literal notranslate"><span class="pre">Genome.get_primitive_map()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="kb_ops.html">KB Ops</a><ul>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.get_kb_subset"><code class="docutils literal notranslate"><span class="pre">get_kb_subset()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.get_models_containing_symbol"><code class="docutils literal notranslate"><span class="pre">get_models_containing_symbol()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.get_models_containing_symbol_strict"><code class="docutils literal notranslate"><span class="pre">get_models_containing_symbol_strict()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.is_abstracted_symbol"><code class="docutils literal notranslate"><span class="pre">is_abstracted_symbol()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.list_models"><code class="docutils literal notranslate"><span class="pre">list_models()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.list_symbols"><code class="docutils literal notranslate"><span class="pre">list_symbols()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.merge_kbs"><code class="docutils literal notranslate"><span class="pre">merge_kbs()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.merge_single_node_kb"><code class="docutils literal notranslate"><span class="pre">merge_single_node_kb()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.recursive_delete_model"><code class="docutils literal notranslate"><span class="pre">recursive_delete_model()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.recursive_update_model"><code class="docutils literal notranslate"><span class="pre">recursive_update_model()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="kb_ops.html#ia.gaius.kb_ops.remove_abstracted_symbols"><code class="docutils literal notranslate"><span class="pre">remove_abstracted_symbols()</span></code></a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="data_ops.html">Data Ops</a><ul>
<li class="toctree-l3"><a class="reference internal" href="data_ops.html#data">Data</a><ul>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.Data"><code class="docutils literal notranslate"><span class="pre">Data</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.Data.__init__"><code class="docutils literal notranslate"><span class="pre">Data.__init__()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.Data.prep"><code class="docutils literal notranslate"><span class="pre">Data.prep()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="data_ops.html#datarecords">DataRecords</a><ul>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.DataRecords"><code class="docutils literal notranslate"><span class="pre">DataRecords</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.DataRecords.__init__"><code class="docutils literal notranslate"><span class="pre">DataRecords.__init__()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="data_ops.html#data-ops-module">data_ops module</a><ul>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.PreparedData"><code class="docutils literal notranslate"><span class="pre">PreparedData</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.PreparedData.prep"><code class="docutils literal notranslate"><span class="pre">PreparedData.prep()</span></code></a></li>
</ul>
</li>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.atoi"><code class="docutils literal notranslate"><span class="pre">atoi()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.natural_keys"><code class="docutils literal notranslate"><span class="pre">natural_keys()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.raw_in_count"><code class="docutils literal notranslate"><span class="pre">raw_in_count()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="data_ops.html#ia.gaius.data_ops.validate_data"><code class="docutils literal notranslate"><span class="pre">validate_data()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="utils.html">Utilities</a><ul>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.GDFFormatError"><code class="docutils literal notranslate"><span class="pre">GDFFormatError</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.abstract_names"><code class="docutils literal notranslate"><span class="pre">abstract_names()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.build_pipeline_layers"><code class="docutils literal notranslate"><span class="pre">build_pipeline_layers()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.create_gdf"><code class="docutils literal notranslate"><span class="pre">create_gdf()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.dict_to_plotly_string"><code class="docutils literal notranslate"><span class="pre">dict_to_plotly_string()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.find_output_slots_and_add_to_end"><code class="docutils literal notranslate"><span class="pre">find_output_slots_and_add_to_end()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.load_sequence_from_file"><code class="docutils literal notranslate"><span class="pre">load_sequence_from_file()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.log_progress"><code class="docutils literal notranslate"><span class="pre">log_progress()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.merge_gdfs"><code class="docutils literal notranslate"><span class="pre">merge_gdfs()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.node_data_to_plotly_string"><code class="docutils literal notranslate"><span class="pre">node_data_to_plotly_string()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.plot_directed_networkx_graph"><code class="docutils literal notranslate"><span class="pre">plot_directed_networkx_graph()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.retrieve_bottom_level_records"><code class="docutils literal notranslate"><span class="pre">retrieve_bottom_level_records()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="utils.html#ia.gaius.utils.write_gdf_to_file"><code class="docutils literal notranslate"><span class="pre">write_gdf_to_file()</span></code></a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="PVT.html">Performance Validation Testing</a><ul>
<li class="toctree-l3"><a class="reference internal" href="PVT.html#performance-validation-test">Performance Validation Test</a></li>
<li class="toctree-l3"><a class="reference internal" href="PVT.html#mongodata">MongoData</a><ul>
<li class="toctree-l4"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData"><code class="docutils literal notranslate"><span class="pre">MongoData</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.__init__"><code class="docutils literal notranslate"><span class="pre">MongoData.__init__()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.convertBinaryStringtoSequence"><code class="docutils literal notranslate"><span class="pre">MongoData.convertBinaryStringtoSequence()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.delete_dataset"><code class="docutils literal notranslate"><span class="pre">MongoData.delete_dataset()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.getSequence"><code class="docutils literal notranslate"><span class="pre">MongoData.getSequence()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.prep"><code class="docutils literal notranslate"><span class="pre">MongoData.prep()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.retrieveDataRecord"><code class="docutils literal notranslate"><span class="pre">MongoData.retrieveDataRecord()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.setIterMode"><code class="docutils literal notranslate"><span class="pre">MongoData.setIterMode()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoData.upload_dataset"><code class="docutils literal notranslate"><span class="pre">MongoData.upload_dataset()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="PVT.html#mongodatarecords">MongoDataRecords</a><ul>
<li class="toctree-l4"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoDataRecords"><code class="docutils literal notranslate"><span class="pre">MongoDataRecords</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoDataRecords.__init__"><code class="docutils literal notranslate"><span class="pre">MongoDataRecords.__init__()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="PVT.html#mongoresults">MongoResults</a><ul>
<li class="toctree-l4"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults"><code class="docutils literal notranslate"><span class="pre">MongoResults</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults.__init__"><code class="docutils literal notranslate"><span class="pre">MongoResults.__init__()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults.addLogRecord"><code class="docutils literal notranslate"><span class="pre">MongoResults.addLogRecord()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults.deleteResults"><code class="docutils literal notranslate"><span class="pre">MongoResults.deleteResults()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults.reset"><code class="docutils literal notranslate"><span class="pre">MongoResults.reset()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults.retrieveResults"><code class="docutils literal notranslate"><span class="pre">MongoResults.retrieveResults()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="PVT.html#ia.gaius.pvt.mongo_interface.MongoResults.saveResults"><code class="docutils literal notranslate"><span class="pre">MongoResults.saveResults()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="PVT.html#pvt-utils">PVT Utils</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="AgentManager.html">AgentManager</a><ul>
<li class="toctree-l3"><a class="reference internal" href="AgentManager.html#id1">AgentManager</a><ul>
<li class="toctree-l4"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager"><code class="docutils literal notranslate"><span class="pre">AgentManager</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.__init__"><code class="docutils literal notranslate"><span class="pre">AgentManager.__init__()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.add_genome"><code class="docutils literal notranslate"><span class="pre">AgentManager.add_genome()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.agent_context"><code class="docutils literal notranslate"><span class="pre">AgentManager.agent_context()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.delete_agent"><code class="docutils literal notranslate"><span class="pre">AgentManager.delete_agent()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.delete_comcom"><code class="docutils literal notranslate"><span class="pre">AgentManager.delete_comcom()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.delete_genome"><code class="docutils literal notranslate"><span class="pre">AgentManager.delete_genome()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.delete_tf"><code class="docutils literal notranslate"><span class="pre">AgentManager.delete_tf()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.get_all_agent_status"><code class="docutils literal notranslate"><span class="pre">AgentManager.get_all_agent_status()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.get_genome"><code class="docutils literal notranslate"><span class="pre">AgentManager.get_genome()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.kill_all_agents"><code class="docutils literal notranslate"><span class="pre">AgentManager.kill_all_agents()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.list_genomes"><code class="docutils literal notranslate"><span class="pre">AgentManager.list_genomes()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.remediate_dead_agents"><code class="docutils literal notranslate"><span class="pre">AgentManager.remediate_dead_agents()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.start_agent"><code class="docutils literal notranslate"><span class="pre">AgentManager.start_agent()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.start_comcom"><code class="docutils literal notranslate"><span class="pre">AgentManager.start_comcom()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.start_hoster"><code class="docutils literal notranslate"><span class="pre">AgentManager.start_hoster()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.start_tf"><code class="docutils literal notranslate"><span class="pre">AgentManager.start_tf()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.stop_hoster"><code class="docutils literal notranslate"><span class="pre">AgentManager.stop_hoster()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentManager.update_current_agents"><code class="docutils literal notranslate"><span class="pre">AgentManager.update_current_agents()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="AgentManager.html#agentinfo">AgentInfo</a><ul>
<li class="toctree-l4"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo"><code class="docutils literal notranslate"><span class="pre">AgentInfo</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.__init__"><code class="docutils literal notranslate"><span class="pre">AgentInfo.__init__()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.check_running"><code class="docutils literal notranslate"><span class="pre">AgentInfo.check_running()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.connect_jia"><code class="docutils literal notranslate"><span class="pre">AgentInfo.connect_jia()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.delete_config_file"><code class="docutils literal notranslate"><span class="pre">AgentInfo.delete_config_file()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.fromFile"><code class="docutils literal notranslate"><span class="pre">AgentInfo.fromFile()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.fromJSON"><code class="docutils literal notranslate"><span class="pre">AgentInfo.fromJSON()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.get_agent_client"><code class="docutils literal notranslate"><span class="pre">AgentInfo.get_agent_client()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.get_docker_networks"><code class="docutils literal notranslate"><span class="pre">AgentInfo.get_docker_networks()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.kill_agent"><code class="docutils literal notranslate"><span class="pre">AgentInfo.kill_agent()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.save_config_file"><code class="docutils literal notranslate"><span class="pre">AgentInfo.save_config_file()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.spawn"><code class="docutils literal notranslate"><span class="pre">AgentInfo.spawn()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.AgentInfo.toJSON"><code class="docutils literal notranslate"><span class="pre">AgentInfo.toJSON()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l3"><a class="reference internal" href="AgentManager.html#tfinfo">TFInfo</a><ul>
<li class="toctree-l4"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo"><code class="docutils literal notranslate"><span class="pre">TFInfo</span></code></a><ul>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.__init__"><code class="docutils literal notranslate"><span class="pre">TFInfo.__init__()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.connect_agents"><code class="docutils literal notranslate"><span class="pre">TFInfo.connect_agents()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.delete_config_file"><code class="docutils literal notranslate"><span class="pre">TFInfo.delete_config_file()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.fromFile"><code class="docutils literal notranslate"><span class="pre">TFInfo.fromFile()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.fromJSON"><code class="docutils literal notranslate"><span class="pre">TFInfo.fromJSON()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.kill"><code class="docutils literal notranslate"><span class="pre">TFInfo.kill()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.save_config_file"><code class="docutils literal notranslate"><span class="pre">TFInfo.save_config_file()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.spawn"><code class="docutils literal notranslate"><span class="pre">TFInfo.spawn()</span></code></a></li>
<li class="toctree-l5"><a class="reference internal" href="AgentManager.html#ia.gaius.manager.TFInfo.toJSON"><code class="docutils literal notranslate"><span class="pre">TFInfo.toJSON()</span></code></a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="prediction_models.html">Prediction Models</a><ul>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.average_emotives"><code class="docutils literal notranslate"><span class="pre">average_emotives()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.bucket_predictions"><code class="docutils literal notranslate"><span class="pre">bucket_predictions()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.hive_model_classification"><code class="docutils literal notranslate"><span class="pre">hive_model_classification()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.hive_model_emotives"><code class="docutils literal notranslate"><span class="pre">hive_model_emotives()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.model_per_emotive"><code class="docutils literal notranslate"><span class="pre">model_per_emotive()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.most_common_ensemble_model_classification"><code class="docutils literal notranslate"><span class="pre">most_common_ensemble_model_classification()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.prediction_ensemble_model_classification"><code class="docutils literal notranslate"><span class="pre">prediction_ensemble_model_classification()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.prediction_ensemble_modeled_emotives"><code class="docutils literal notranslate"><span class="pre">prediction_ensemble_modeled_emotives()</span></code></a></li>
<li class="toctree-l3"><a class="reference internal" href="prediction_models.html#ia.gaius.prediction_models.principal_delta"><code class="docutils literal notranslate"><span class="pre">principal_delta()</span></code></a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="ia.gaius.html">ia.gaius package</a><ul>
<li class="toctree-l3"><a class="reference internal" href="ia.gaius.html#subpackages">Subpackages</a><ul>
<li class="toctree-l4"><a class="reference internal" href="ia.gaius.tests.html">ia.gaius.tests package</a><ul>
<li class="toctree-l5"><a class="reference internal" href="ia.gaius.tests.html#submodules">Submodules</a></li>
<li class="toctree-l5"><a class="reference internal" href="ia.gaius.tests.html#module-ia.gaius.tests.classification">ia.gaius.tests.classification module</a><ul>
<li class="toctree-l6"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.classification.Tester"><code class="docutils literal notranslate"><span class="pre">Tester</span></code></a><ul>
<li class="toctree-l7"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.classification.Tester.next_test_prep"><code class="docutils literal notranslate"><span class="pre">Tester.next_test_prep()</span></code></a></li>
<li class="toctree-l7"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.classification.Tester.test"><code class="docutils literal notranslate"><span class="pre">Tester.test()</span></code></a></li>
<li class="toctree-l7"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.classification.Tester.train"><code class="docutils literal notranslate"><span class="pre">Tester.train()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l5"><a class="reference internal" href="ia.gaius.tests.html#module-ia.gaius.tests.utility">ia.gaius.tests.utility module</a><ul>
<li class="toctree-l6"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.utility.Tester"><code class="docutils literal notranslate"><span class="pre">Tester</span></code></a><ul>
<li class="toctree-l7"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.utility.Tester.next_test_prep"><code class="docutils literal notranslate"><span class="pre">Tester.next_test_prep()</span></code></a></li>
<li class="toctree-l7"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.utility.Tester.test"><code class="docutils literal notranslate"><span class="pre">Tester.test()</span></code></a></li>
<li class="toctree-l7"><a class="reference internal" href="ia.gaius.tests.html#ia.gaius.tests.utility.Tester.train"><code class="docutils literal notranslate"><span class="pre">Tester.train()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l5"><a class="reference internal" href="ia.gaius.tests.html#module-ia.gaius.tests">Module contents</a></li>
</ul>
</li>
<li class="toctree-l4"><a class="reference internal" href="ia.gaius.html#submodules">Submodules</a></li>
<li class="toctree-l4"><a class="reference internal" href="ia.gaius.html#ia-gaius-back-testing-module">ia.gaius.back_testing module</a></li>
<li class="toctree-l4"><a class="reference internal" href="ia.gaius.html#module-ia.gaius.data_language">ia.gaius.data_language module</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="examples/UsageExamples.html">Examples</a><ul>
<li class="toctree-l2"><a class="reference internal" href="examples/Agent%20Setup.html">Agent Setup</a></li>
<li class="toctree-l2"><a class="reference internal" href="examples/Changing%20Genes.html">Changing Genes</a></li>
<li class="toctree-l2"><a class="reference internal" href="examples/Training%201.html">Basic PVT Setup and Example</a><ul>
<li class="toctree-l3"><a class="reference internal" href="examples/Training%201.html#Iris-Dataset-Training">Iris Dataset Training</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html">PVT on 10k records of MNIST Digit Dataset</a><ul>
<li class="toctree-l3"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html#Setup-Agent">Setup Agent</a></li>
<li class="toctree-l3"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html#Load-Data">Load Data</a></li>
<li class="toctree-l3"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html#Run-PVT">Run PVT</a></li>
<li class="toctree-l3"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html#Show-results">Show results</a></li>
<li class="toctree-l3"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html#Teardown-agent">Teardown agent</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="examples/sklearn_mnist.html">Scikit-Learn GAIuS™ Pipeline Example</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="cognitive_processor/Genes.html">Cognitive Processor Genes</a></li>
<li class="toctree-l1"><a class="reference internal" href="cognitive_processor/Genes.html#gene-information">Gene Information</a><ul>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#always-update-frequencies">always_update_frequencies</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#auto-learn-algorithm">auto_learn_algorithm</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#auto-learn-metric">auto_learn_metric</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#classifier">classifier</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#enable-genome-snapshots">enable_genome_snapshots</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#enable-predictions-kb">enable_predictions_kb</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#enable-snapshots">enable_snapshots</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#max-predictions">max_predictions</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#max-sequence-length">max_sequence_length</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#near-vector-count">near_vector_count</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#persistence">persistence</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#predict-on-nth-event">predict_on_nth_event</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-sort-metric">prediction_sort_metric</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-threshold">prediction_threshold</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-threshold-direction">prediction_threshold_direction</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-threshold-metric">prediction_threshold_metric</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#recall-threshold">recall_threshold</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#search-depth">search_depth</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#sort">SORT</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#smoothness">smoothness</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#snapshot-gen-predictions">snapshot_gen_predictions</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#wm-resolution">wm_resolution</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="comcom/COMCOMHead.html">COMCOM System</a><ul>
<li class="toctree-l2"><a class="reference internal" href="comcom/COMCOMClient.html">COMCOMClient</a><ul>
<li class="toctree-l3"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient"><code class="docutils literal notranslate"><span class="pre">COMCOMClient</span></code></a><ul>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.__init__"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.__init__()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.add_function_to_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.add_function_to_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.call_agent_command"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.call_agent_command()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_agents"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_agents()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.clear_outputslot_command_queue"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.clear_outputslot_command_queue()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.comcom_to_cytoscape"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.comcom_to_cytoscape()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.connect_to_agent"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.connect_to_agent()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.create_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.create_pipeline()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.delete_function_from_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.delete_function_from_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.delete_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.delete_pipeline()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.desynchronize_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.desynchronize_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.disconnect_agent"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.disconnect_agent()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.disconnect_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.disconnect_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.disconnect_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.disconnect_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_agent_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_agent_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_config_as_json"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_config_as_json()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_dds_message_types"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_dds_message_types()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_debug_topic_data_single"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_debug_topic_data_single()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_debug_topic_data_stream"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_debug_topic_data_stream()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_input_slot_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_input_slot_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_output_slot_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_output_slot_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.get_pipeline_data"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.get_pipeline_data()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.input_slot_to_cytoscape"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.input_slot_to_cytoscape()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_agent_connections"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_agent_connections()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_output_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_output_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_pipelines"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_pipelines()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.list_preprocessing_functions"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.list_preprocessing_functions()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.load_comcom_config"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.load_comcom_config()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.modify_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.modify_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.modify_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.modify_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.modify_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.modify_pipeline()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.pipeline_to_cytoscape"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.pipeline_to_cytoscape()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.query_db"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.query_db()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.query_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.query_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.synchronize_input_slots"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.synchronize_input_slots()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.toggle_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.toggle_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.toggle_output_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.toggle_output_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.visualize_comcom"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.visualize_comcom()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.visualize_input_slot"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.visualize_input_slot()</span></code></a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/COMCOMClient.html#ia.gaius.experimental.comcom_client.COMCOMClient.visualize_pipeline"><code class="docutils literal notranslate"><span class="pre">COMCOMClient.visualize_pipeline()</span></code></a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="comcom/InputSlot.html">ComCom InputSlot</a><ul>
<li class="toctree-l3"><a class="reference internal" href="comcom/InputSlot.html#relevant-inputslot-functions">Relevant InputSlot Functions</a></li>
<li class="toctree-l3"><a class="reference internal" href="comcom/InputSlot.html#types-of-inputslots">Types of InputSlots</a><ul>
<li class="toctree-l4"><a class="reference internal" href="comcom/InputSlot.html#comcomddslistener">COMCOMDDSListener</a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/InputSlot.html#comcomfilehandler">COMCOMFileHandler</a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/InputSlot.html#comcomweblistener">COMCOMWebListener</a></li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="comcom/OutputSlot.html">ComCom OutputSlot</a><ul>
<li class="toctree-l3"><a class="reference internal" href="comcom/OutputSlot.html#relevant-outputslot-functions">Relevant OutputSlot Functions</a></li>
<li class="toctree-l3"><a class="reference internal" href="comcom/OutputSlot.html#types-of-outputslots">Types of OutputSlots</a><ul>
<li class="toctree-l4"><a class="reference internal" href="comcom/OutputSlot.html#comcomrestapipublisher">COMCOMRESTAPIPublisher</a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/OutputSlot.html#comcomagentstreamer">COMCOMAgentStreamer</a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/OutputSlot.html#comcomddsstreamer">COMCOMDDSStreamer</a></li>
<li class="toctree-l4"><a class="reference internal" href="comcom/OutputSlot.html#comcomtcpsocketstreamer">COMCOMTCPSocketStreamer</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="REST.html">GAIuS RESTful API</a><ul>
<li class="toctree-l2"><a class="reference internal" href="REST.html#four-core-api-calls">Four Core API Calls</a></li>
<li class="toctree-l2"><a class="reference internal" href="REST.html#helper-functionality">Helper Functionality</a></li>
<li class="toctree-l2"><a class="reference internal" href="REST.html#miscellaneous-endpoints">Miscellaneous Endpoints</a></li>
</ul>
</li>
</ul>

        </div>
      </div>
    </nav>

    <section data-toggle="wy-nav-shift" class="wy-nav-content-wrap"><nav class="wy-nav-top" aria-label="Mobile navigation menu" >
          <i data-toggle="wy-nav-top" class="fa fa-bars"></i>
          <a href="#">IA-SDK-Python</a>
      </nav>

      <div class="wy-nav-content">
        <div class="rst-content">
          <div role="navigation" aria-label="Page navigation">
  <ul class="wy-breadcrumbs">
      <li><a href="#" class="icon icon-home" aria-label="Home"></a></li>
      <li class="breadcrumb-item active">IA-SDK Python documentation!</li>
      <li class="wy-breadcrumbs-aside">
            <a href="_sources/index.rst.txt" rel="nofollow"> View page source</a>
      </li>
  </ul>
  <hr/>
</div>
          <div role="main" class="document" itemscope="itemscope" itemtype="http://schema.org/Article">
           <div itemprop="articleBody">
             
  <script>
document.addEventListener("DOMContentLoaded", function(event) {
  if (typeof navigator.serviceWorker !== 'undefined')
  {
  navigator.serviceWorker.register('/sw.js').then(function(registration)
  {
    var manifest = document.createElement('link');
    manifest.rel = 'manifest';
    manifest.href = '/manifest.json';
    document.head.appendChild(manifest);
});
  $('head').append('<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">')
  $('head').append('<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">')
  $('head').append('<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png"></div>')
  }
});
</script><section id="ia-sdk-python-documentation">
<h1>IA-SDK Python documentation!<a class="headerlink" href="#ia-sdk-python-documentation" title="Link to this heading"></a></h1>
<p>This project provides various helper classes and functions for interacting with GAIuS™ agents. For more information, see <a class="reference external" href="https://intelligent-artifacts.com/">Intelligent Artifacts’ site</a></p>
<div class="toctree-wrapper compound">
<p class="caption" role="heading"><span class="caption-text">Contents:</span></p>
<ul>
<li class="toctree-l1"><a class="reference internal" href="GDF.html">GAIuS Data Format (GDF)</a><ul>
<li class="toctree-l2"><a class="reference internal" href="GDF.html#fields">Fields</a></li>
<li class="toctree-l2"><a class="reference internal" href="GDF.html#example-conversions">Example Conversions</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="Tutorials.html">Tutorials</a><ul>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Quick%20Start%20-%20Hello%2C%20World%21.html">Quick Start: Hello, World!</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Genome%20Introduction.html">Create a Genome Topology for your Agent</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Creation.html">Deploy an Agent</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Creation.html#Connect-to-Your-Agent">Connect to Your Agent</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Strings.html">Interact with your Agent using String Data</a></li>
<li class="toctree-l2"><a class="reference internal" href="tutorial_segments/Agent%20Observe%20Emotives.html">An Emotional Machine: Emotives and Mood</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="API.html">API Reference</a><ul>
<li class="toctree-l2"><a class="reference internal" href="AgentClient.html">AgentClient</a></li>
<li class="toctree-l2"><a class="reference internal" href="ThinkfluxClient.html">Thinkflux Client</a></li>
<li class="toctree-l2"><a class="reference internal" href="comcom/COMCOMClient.html">COMCOMClient</a></li>
<li class="toctree-l2"><a class="reference internal" href="Genome.html">Genome</a></li>
<li class="toctree-l2"><a class="reference internal" href="kb_ops.html">KB Ops</a></li>
<li class="toctree-l2"><a class="reference internal" href="data_ops.html">Data Ops</a></li>
<li class="toctree-l2"><a class="reference internal" href="utils.html">Utilities</a></li>
<li class="toctree-l2"><a class="reference internal" href="PVT.html">Performance Validation Testing</a></li>
<li class="toctree-l2"><a class="reference internal" href="AgentManager.html">AgentManager</a></li>
<li class="toctree-l2"><a class="reference internal" href="prediction_models.html">Prediction Models</a></li>
<li class="toctree-l2"><a class="reference internal" href="ia.gaius.html">ia.gaius package</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="examples/UsageExamples.html">Examples</a><ul>
<li class="toctree-l2"><a class="reference internal" href="examples/Agent%20Setup.html">Agent Setup</a></li>
<li class="toctree-l2"><a class="reference internal" href="examples/Changing%20Genes.html">Changing Genes</a></li>
<li class="toctree-l2"><a class="reference internal" href="examples/Training%201.html">Basic PVT Setup and Example</a></li>
<li class="toctree-l2"><a class="reference internal" href="examples/pvt_agent_manager_mnist10k.html">PVT on 10k records of MNIST Digit Dataset</a></li>
<li class="toctree-l2"><a class="reference internal" href="examples/sklearn_mnist.html">Scikit-Learn GAIuS™ Pipeline Example</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="cognitive_processor/Genes.html">Cognitive Processor Genes</a></li>
<li class="toctree-l1"><a class="reference internal" href="cognitive_processor/Genes.html#gene-information">Gene Information</a><ul>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#always-update-frequencies">always_update_frequencies</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#auto-learn-algorithm">auto_learn_algorithm</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#auto-learn-metric">auto_learn_metric</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#classifier">classifier</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#enable-genome-snapshots">enable_genome_snapshots</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#enable-predictions-kb">enable_predictions_kb</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#enable-snapshots">enable_snapshots</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#max-predictions">max_predictions</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#max-sequence-length">max_sequence_length</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#near-vector-count">near_vector_count</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#persistence">persistence</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#predict-on-nth-event">predict_on_nth_event</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-sort-metric">prediction_sort_metric</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-threshold">prediction_threshold</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-threshold-direction">prediction_threshold_direction</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#prediction-threshold-metric">prediction_threshold_metric</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#recall-threshold">recall_threshold</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#search-depth">search_depth</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#sort">SORT</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#smoothness">smoothness</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#snapshot-gen-predictions">snapshot_gen_predictions</a></li>
<li class="toctree-l2"><a class="reference internal" href="cognitive_processor/Genes.html#wm-resolution">wm_resolution</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="comcom/COMCOMHead.html">COMCOM System</a><ul>
<li class="toctree-l2"><a class="reference internal" href="comcom/COMCOMClient.html">COMCOMClient</a></li>
<li class="toctree-l2"><a class="reference internal" href="comcom/InputSlot.html">ComCom InputSlot</a></li>
<li class="toctree-l2"><a class="reference internal" href="comcom/OutputSlot.html">ComCom OutputSlot</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="REST.html">GAIuS RESTful API</a><ul>
<li class="toctree-l2"><a class="reference internal" href="REST.html#four-core-api-calls">Four Core API Calls</a></li>
<li class="toctree-l2"><a class="reference internal" href="REST.html#helper-functionality">Helper Functionality</a></li>
<li class="toctree-l2"><a class="reference internal" href="REST.html#miscellaneous-endpoints">Miscellaneous Endpoints</a></li>
</ul>
</li>
</ul>
</div>
</section>
<section id="indices-and-tables">
<h1>Indices and tables<a class="headerlink" href="#indices-and-tables" title="Link to this heading"></a></h1>
<ul class="simple">
<li><p><a class="reference internal" href="genindex.html"><span class="std std-ref">Index</span></a></p></li>
<li><p><a class="reference internal" href="py-modindex.html"><span class="std std-ref">Module Index</span></a></p></li>
<li><p><a class="reference internal" href="search.html"><span class="std std-ref">Search Page</span></a></p></li>
</ul>
</section>


           </div>
          </div>
          <footer><div class="rst-footer-buttons" role="navigation" aria-label="Footer">
        <a href="GDF.html" class="btn btn-neutral float-right" title="GAIuS Data Format (GDF)" accesskey="n" rel="next">Next <span class="fa fa-arrow-circle-right" aria-hidden="true"></span></a>
    </div>

  <hr/>

  <div role="contentinfo">
    <p>&#169; Copyright 2023, Intelligent Artifacts Inc.</p>
  </div>

  Built with <a href="https://www.sphinx-doc.org/">Sphinx</a> using a
    <a href="https://github.com/readthedocs/sphinx_rtd_theme">theme</a>
    provided by <a href="https://readthedocs.org">Read the Docs</a>.
   

</footer>
        </div>
      </div>
    </section>
  </div>
  <script>
      jQuery(function () {
          SphinxRtdTheme.Navigation.enable(true);
      });
  </script> 

</body>
</html>
