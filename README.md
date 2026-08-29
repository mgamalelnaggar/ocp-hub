For any new environment, create following files



$root/values-{}.yaml. This is replica from values-hub.yaml file, with some minor changes



$root/{}-app-values directory with the following values files tailored to this enfironment:
- values-logging-clf.yaml --> details about logs forwarding
- values-odf-multus.yaml --> details about odf networking in case multus is used
