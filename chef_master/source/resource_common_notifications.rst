=====================================================
Notifications for Recipes and Resources
=====================================================

.. include:: ../../swaps/swap_desc_a.txt
.. include:: ../../swaps/swap_desc_b.txt
.. include:: ../../swaps/swap_desc_c.txt
.. include:: ../../swaps/swap_desc_d.txt
.. include:: ../../swaps/swap_desc_e.txt
.. include:: ../../swaps/swap_desc_f.txt
.. include:: ../../swaps/swap_desc_g.txt
.. include:: ../../swaps/swap_desc_h.txt
.. include:: ../../swaps/swap_desc_i.txt
.. include:: ../../swaps/swap_desc_j.txt
.. include:: ../../swaps/swap_desc_k.txt
.. include:: ../../swaps/swap_desc_l.txt
.. include:: ../../swaps/swap_desc_m.txt
.. include:: ../../swaps/swap_desc_n.txt
.. include:: ../../swaps/swap_desc_o.txt
.. include:: ../../swaps/swap_desc_p.txt
.. include:: ../../swaps/swap_desc_q.txt
.. include:: ../../swaps/swap_desc_r.txt
.. include:: ../../swaps/swap_desc_s.txt
.. include:: ../../swaps/swap_desc_t.txt
.. include:: ../../swaps/swap_desc_u.txt
.. include:: ../../swaps/swap_desc_v.txt
.. include:: ../../swaps/swap_desc_w.txt
.. include:: ../../swaps/swap_desc_x.txt
.. include:: ../../swaps/swap_desc_y.txt
.. include:: ../../swaps/swap_desc_z.txt
.. include:: ../../swaps/swap_http.txt
.. include:: ../../swaps/swap_names.txt
.. include:: ../../swaps/swap_notes.txt

.. include:: ../../includes_cookbooks/includes_cookbooks_resource_common_notifications.rst

Notifications Timers
=====================================================
.. include:: ../../includes_cookbooks/includes_cookbooks_resource_common_notifications_timers.rst

Notifies Syntax
=====================================================
.. include:: ../../includes_cookbooks/includes_cookbooks_resource_common_notifications_syntax_notifies.rst

Examples
-----------------------------------------------------
The following examples show how to use the ``notifies`` notification in a recipe.

**Delay notifications**

.. include:: ../../step_resource/step_resource_template_notifies_delay.rst

**Notify immediately**

.. include:: ../../step_resource/step_resource_template_notifies_run_immediately.rst

**Enable a service after a restart or reload**

.. include:: ../../step_resource/step_resource_service_notifies_enable_after_restart_or_reload.rst

**Notify multiple resources**

.. include:: ../../step_resource/step_resource_template_notifies_multiple_resources.rst

**Notify in a specific order**

.. include:: ../../step_resource/step_resource_execute_notifies_specific_order.rst

**Restart when a configuration is broken**

.. include:: ../../step_resource/step_resource_execute_notifies_prevent_restart_if_config_is_broken.rst

**Reload a service**

.. include:: ../../step_resource/step_resource_template_notifies_reload_service.rst

**Restart a service when a template is modified**

.. include:: ../../step_resource/step_resource_template_notifies_restart_service_when_template_modified.rst

**Send notifications to multiple resources**

.. include:: ../../step_resource/step_resource_template_notifies_send_notifications_to_multiple_resources.rst


Subscribes Syntax
=====================================================
.. include:: ../../includes_cookbooks/includes_cookbooks_resource_common_notifications_syntax_subscribes.rst

Examples
-----------------------------------------------------
The following examples show how to use the ``subscribes`` notification in a recipe.

**Prevent restart and reconfigure if configuration is broken**

.. include:: ../../step_resource/step_resource_execute_subscribes_prevent_restart_and_reconfigure.rst

**Reload a service using a template**

.. include:: ../../step_resource/step_resource_service_subscribes_reload_using_template.rst
