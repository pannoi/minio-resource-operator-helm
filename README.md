helm package kubernetes/
mv $FILE packages/
helm repo index packages/
