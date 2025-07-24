# Spark-Cluster-setup
Epay SBI
491  oc auth can-i create pods --as=epayuser -n dev-spark
  492  oc auth can-i create pods --as=epayuser -n dev-spark-poc
  493  oc get project | grep -i dev-spark
  494  oc project dev-spark
  495  ls
  496  ls -a
  497  ls -ll
  498  la
  499  ls
  500  ls -lrt
  501  oc get pods
  502  oc describe pod spark-pod
  503  oc get pod
  504  oc describe pod spark-pod
  505  oc get pods
  506  oc delete pod spark-pod
  507  oc get svc -n dev-spark
  508  oc get pods
  509  oc exec -it spark-pod /bin/bash
  510  oc get pods
  511  oc exec spark-pod -n dev-spark --/bin/bash
  512  oc exec spark-pod -n dev-spark -- /bin/bash
  513  oc exec spark-pod -n dev-spark -- /bin/sh
  514  oc get svc
  515  curl spark-pod:8080
  516  oc get all
  517  oc exec -it spark-pod -n spark-dev --/bin/bash
  518  oc exec -it spark-pod -n spark-dev -- /bin/bash
  519  oc exec -it spark-pod -n dev-spark -- /bin/bash
  520  whoami
  521  pwd
  522  oc get projects | grep -i dev-spark
  523  oc get projects
  524  oc get projects | grep -i spark
  525  oc get dev-spark-cluster
  526  oc project dev-spark-cluster
  527  ls
  528  cd spark/ls
  529  ls
  530  cd spark/
  531  ls
  532  oc apply -f spark.yaml
  533  oc get pods
  534  oc describe pod spark-pod
  535  oc get logs spark-pod
  536  oc get pods
  537  oc delete pod spark-pod
  538  oc apply -f spark.yaml
  539  oc get pods
  540  oc delete pod spark-pod
  541  ls
  542  cat spark-service.yaml
  543  cat spark.yaml
  544  df -h
  545  ls
  546  cat spark.yaml
  547  ll
  548  cd ..
  549  ls
  550  cat telnet.yaml
  551  ls
  552  ll
  553  cd spsark
  554  cd spark
  555  ls
  556  oc apply -f spark.yaml
  557  oc get pods
  558  oc delete pod spark-pod
  559  oc get pod
  560  pwd
  561  oc get projects | grep  -i spark
  562  pwd
  563  ls
  564  oc get projects
  565  cd
  566  pwd
  567  oc get projects
  568  oc get project
  569  ls
  570  history
  571  oc get projects
  572  ls
  573  hostname
  574  oc get project
  575  ls
  576  cd ..
  577  ls
  578  oc get project
  579  ls
  580  cd epsyuser
  581  ls -lrt
  582  cd epayuser
  583  ls
  584  oc get project
  585  exit
  586  oc get projects
  587  oc get ns
  588  oc get ns | grep -i dev
  589  oc get po -n dev-spark
  590  oc project dev-spark
  591  ls -la
  592  kc
  593  oc get po -n dev-rns
  594  oc get ns
  595  oc get ns| grep -i dev
  596  oc get po -n dev-transaction
  597  oc logs -f txn-transactionservice-6dc6c6b8d8-rpqz5 -n dev-transaction -p
  598  oc get po -n dev-transaction
  599  oc get po -n dev-admin
  600  oc logs -f admin-adminservice-54556c495d-gl9vn -n dev-admin
  601  oc get po -n dev-admin
  602  oc get po -n dev-rns
  603  oc get po -n dev-simulators
  604  oc get svc -n dev-simulators
  605  oc get po -n dev-simulators
  606  oc get svc -n dev-simulators
  607  oc get svc -n dev-simulators dev-simulator-merchant-simulator -o yaml
  608  oc get ns | grep -i uat
  609  oc get po -n uat-admin
  610  oc get ns
  611  oc get ns | grep -i perf-admin
  612  oc get -n perf-admin
  613  oc get ns | grep -i perf-admin
  614  ls
  615  oc get project
  616  oc get projects
  617  oc projects |grep uat
  618  oc project uat-frontend
  619  oc get po
  620  oc describe po uat-merchantfe-merchantfe-service-5c6cfcfc5c-92nv7
  621  hostname
  622  oc get ns |grep sit
  623  oc project sit-transaction
  624  oc get po
  625  oc get deploy
  626  oc rollout restart deploy txn-transactionservice
  627  oc get po
  628  oc delete po txn-transactionservice-57f969c644-sxv7q
  629  oc get po
  630  oc project sit-admin
  631  oc get po
  632  oc get po -n sit-frontend
  633  oc get po -n sit-kms
  634  oc get po -n sit-merchant
  635  oc describe po merchant-merchantservice-797dd684b8-9bgrb
  636  oc describe po merchant-merchantservice-797dd684b8-9bgrb -n sit-merchant
  637  oc get po -n sit-merchant
  638  oc logs -f   Warning  BackOff  3m28s (x38089 over 5d22h)  kubelet  Back-off restarting failed container merchantservice in pod merchant-merchantservice-797dd684b8-9bgrb_sit-merchant(6210afb7-5e63-4e33-b404-a6dea6f1421d)
  639  oc logs -f merchant-merchantservice-797dd684b8-9bgrb
  640  oc logs -f merchant-merchantservice-797dd684b8-9bgrb -n sit-merchant
  641  hostname
  642  oc get po
  643  oc project
  644  oc get ns |grep dev
  645  podman -v
  646  podman images
  647  oc get po
  648  oc login -u V1018653
  649  oc get po
  650  oc project dev-spark
  651  ]
  652  oc get po
  653  ll  /usr/local/bin/oc
  654  su - epay1
  655  pwd
  656  helm
  657  exit
  658  oc whoami
  659  logout
  660  exit
  661  helm
  662  bash
  663  oc whoami
  664  oc login -u 6692435
  665  ls -l
  666  cd epay_deven/spark/spark-kubernetes-operator-main/
  667  ls -l
  668  cd build-tools/
  669  ls -l
  670  cd helm
  671  ls -l
  672  pwd
  673  ls -lrth spark-kubernetes-operator
  674  oc project
  675  helm install spark-operator spark-kubernetes-operator/
  676  oc get po
  677  oc get events
  678  oc get pvc
  679  oc create sa spark-operator-sa
  680  oc adm policy add-scc-to-user anyuid -z spark-operator-sa
  681  oc get po
  682  helm uninstall spark-operator spark-kubernetes-operator/
  683  helm install spark-operator spark-kubernetes-operator/
  684  oc get po
  685  oc get events
  686  oc get project
  687  oc project dev-spark
  688  ls -la
  689  cat telnet.yaml
  690  oc get po
  691  exit
  692  oc get projects
  693  oc get projects | grep -i dev
  694  oc get po dev-spark-cluster
  695  oc current project
  696  oc get project | grep -i dev-spark
  697  oc get project dev-spark-cluster
  698  ls
  699  cd spark/
  700  ls
  701  oc apply -f spark.yaml
  702  whoami
  703  whoami userid
  704  "V1018653"oc describe pod spark-pod
  705  oc auth can-i create pods -n dev-spark-cluster
  706  oc get events
  707  pwd
  708  history
  709  current project
  710  oc current project
  711  whoim
  712  cd
  713  whoiam
  714  cd spark
  715  ls
  716  ll
  717  oc get events
  718  cd
  719  ls
  720  cd
  721  ls
  722  cd ./
  723  ls
  724  oc get project | grep -i dev
  725  describe dev-spark-cluster
  726  ls
  727  cd spark/
  728  ls
  729  oc apply -f spark.yaml
  730  oc get pods -o wide
  731  ls
  732  oc get ns
  733  oc project
  734  oc grt projects
  735  oc get projects
  736  oc get projects | grep -l dev-spark-cluster
  737  oc get project | grep -l dev-spark-cluster
  738  oc get project | grep -i dev-spark-cluster
  739  cd dev-spark-cluster
  740  oc project dev-spark-cluster
  741  oc project
  742  ls -lrt
  743  ls
  744  oc apply -f spark.yaml
  745  oc get project | grep -i dev-spark
  746  oc get events
  747  ls
  748  vi service.yaml
  749  ls
  750  cat spark-service.yaml
  751  cat spark.yaml
  752  ls
  753  ll
  754  oc apply -f spark.yaml
  755  oc get pv
  756  oc get pvc
  757  oc get pvc -A
  758  oc get pvc -A | grep dev-spark-cluster
  759  whoami
  760  ls
  761  oc get events
  762  hostname
  763  df -h
  764  oc get po
  765  ls -lrth
  766  cd epay_deven/
  767  ls -lrth
  768  cd spark/
  769  ls -lrth
  770  oc projects
  771  oc project openshift-user-workload-monitoring
  772  oc get po -o wide
  773  oc projects | grep -i workload
  774  oc get routes
  775  oc projects
  776  oc get projects
  777  oc get projects | grep user
  778  oc get project openshift-user-workload-monitoring
  779  oc get po
  780  oc get routes
  781  oc get projects | grep monitoring
  782  oc project openshift-monitoring
  783  oc get routes
  784  oc projects
  785  oc project dev-spark
  786  oc get po
  787  oc project dev-spark-cluster
  788  oc get events
  789  oc get po
  790  oc get deployment
  791  ls -lrth
  792  cd ..
  793  ls -lrth
  794  cd ..
  795  ls -lrth
  796  cd spark/
  797  ls -lrth
  798  vi spark.yaml
  799  oc apply -f spark.yaml
  800  cat spark.yaml
  801  oc projects
  802  oc project dev-spark
  803  oc get po
  804  oc create serviceaccount spark-sa -n dev-spark
  805  oc get po
  806  oc adm policy add-scc-to-user anyuid -z spark-sa -n dev-spark
  807  ls -lrth
  808  cd ..
  809  ls -lrthg
  810  cd epay_deven/
  811  ls -lrth
  812  cd spark/
  813  ls -0lrth
  814  ls -=lrth
  815  ls -lrth
  816  oc get sc
  817  vi spark-history-pvc.yaml
  818  oc get pvc
  819  oc apply -f spark-history-pvc.yaml
  820  cat spark-history-pvc.yaml
  821  helm
  822  oc apply -f spark-history-pvc.yaml
  823  ip a
  824  oc apply -f spark-history-pvc.yaml
  825  helm
  826  oc apply -f spark-history-pvc.yaml
  827  helm
  828  oc apply -f spark-history-pvc.yaml
  829  helm
  830  oc apply -f spark-history-pvc.yaml
  831  ls -lrth
  832  cat spark-history-pvc.yaml
  833  vi spark-history-pvc.yaml
  834  oc apply -f spark-history-pvc.yaml
  835  oc project dev-spark
  836  oc get po
  837  ls -lrth
  838  vi ops-service-spark-app.yaml
  839  vi spark-history-server-deployment.yaml
  840  helm
  841  ip a
  842  ls -lrth
  843  unzip spark-kubernetes-operator-main.zip
  844  ls -lrth
  845  ls -lrth spark-kubernetes-operator-main
  846  cat spark-kubernetes-operator-main/gradle.properties
  847  helm install spark-operator spark/spark-kubernetes-operator --namespace spark-dev --create-namespace
  848  helm install spark-operator spark/spark-kubernetes-operator --namespace spark-dev-operator --create-namespace
  849  oc new-project spark-dev-operator
  850  oc new-project dev-spark-operator
  851  oc projects
  852  oc projects | grep
  853  oc projects | grep spark
  854  ls -lrth
  855  oc projects | grep spark
  856  ls -lrth
  857  vi spark-history-pvc.yaml
  858  oc apply -f  spark-history-pvc.yaml
  859  cat spark-history-pvc.yaml
  860  oc project dev-spark-operator
  861  oc get pvc
  862  oc delete -f  spark-history-pvc.yaml
  863  oc projects
  864  oc projects | grep spark
  865  oc project dev-spark
  866  oc get po
  867  helm repo add spark https://apache.github.io/spark-kubernetes-operator
  868  ls -lrth
  869  cd spark-kubernetes-operator-main
  870  ls -lrthg
  871  ls -lrth
  872  cd spark-operator
  873  ls -lrth
  874  cd ..
  875  ls -lrth
  876  cd build-tools
  877  ls -lrth
  878  ls lrth
  879  ls -lrth helm
  880  ls -lrth helm/spark-kubernetes-operator
  881  pwd
  882  ls -lrth helm/spark-kubernetes-operator
  883  ls -lrth helm/spark-kubernetes-operator/values.yaml
  884  cat helm/spark-kubernetes-operator/values.yaml
  885  ls -lrth
  886  ls -lrth helm
  887  ls -lrth helm/spark-kubernetes-operator
  888  cd spark-kubernetes-operator
  889  cd helm
  890  ls -lrth
  891  helm install spark-operator spark-kubernetes-operator/
  892  '
  893  oc projects
  894  oc project dev-spark-operator
  895  helm install spark-operator spark-kubernetes-operator/
  896  ls -lrth
  897  helm install spark-operator spark-kubernetes-operator/
  898  ped
  899  pwd
  900  helm install spark-operator spark-kubernetes-operator/
  901  ls -lrth
  902  cd spa
  903  cd spark-kubernetes-operator
  904  ls -lrth
  905  cd templates/
  906  ls -lrth
  907  vi workload-rbac.yaml
  908  vi spark-operator.yaml
  909  oc get events
  910  vi spark-operator.yaml
  911  oc get scc
  912  ls -lrth
  913  cd ..
  914  ls -lrth
  915  vi values.yaml
  916  ls -lrth
  917  cd ..
  918  ls -lrth
  919  vi sparkoperatorscc.yaml
  920  oc apply -f sparkoperatorscc.yaml
  921  vi sparkoperatorscc.yaml
  922  cat sparkoperatorscc.yaml
  923  oc apply -f sparkoperatorscc.yaml
  924  oc adm policy add-scc-to-user spark-operator-scc system:serviceaccount:dev-spark-operator:spark-operator-sa
  925  oc get po
  926  cat sparkoperatorscc.yaml
  927  oc apply -f sparkoperatorscc.yaml
  928  vi sparkoperatorscc.yaml
  929  oc apply -f sparkoperatorscc.yaml
  930  oc adm policy add-scc-to-user spark-operator-scc system:serviceaccount:dev-spark-operator:spark-operator-sa
  931  oc get po
  932  oc get events
  933  oc get po
  934  ls -lrth
  935  vi spark-kubernetes-operator/values.yaml
  936  oc get po
  937  vi spark-kubernetes-operator/values.yaml
  938  cat spark-kubernetes-operator/values.yaml
  939  ls -lrth
  940  helm install spark-operator spark-kubernetes-operator/
  941  helm list
  942  helm uninstall spark-operator
  943  helm install spark-operator spark-kubernetes-operator/
  944  oc get po
  945  oc get events
  946  oc get po
  947  ls -lrth
  948  oc get pvc
  949  oc get events
  950  ls -lrth
  951  vi sparkoperatorscc.yaml
  952  oc get scc spark-operator-scc
  953  oc get pod spark-kubernetes-operator-58f799b786- -o yaml | oc adm policy scc-subject-review -f -
  954  oc get deployment
  955  oc get events
  956  oc describe deployment spark-kubernetes-operator
  957  vi spark-kubernetes-operator/values.yaml
  958  oc get deployment -o yaml
  959  oc get deployment -o yaml | grep runAsUser
  960  oc get deployment
  961  oc describe sa spark-kubernetes-operator -n dev-spark-operator
  962  oc get sa
  963  oc describe sa spark-operator-sa -n dev-spark-operator
  964  oc get scc | grep spark-operator-scc
  965  oc get po
  966  oc create sa spark-kubernetes-operator -n dev-spark-operator
  967  oc adm policy add-scc-to-user spark-operator-scc -z spark-kubernetes-operator -n dev-spark-operator
  968  oc get sa
  969  oc get pods -w -n dev-spark-operator
  970  oc get po
  971  oc get events -n dev-spark-operator --sort-by='.lastTimestamp'
  972  ls -lrth
  973  vi spark-kubernetes-operator/templates/spark-operator.yaml
  974  vi spark-kubernetes-operator/values.yaml
  975  oc get sa spark-operator -n dev-spark-operator
  976  vi spark-kubernetes-operator/values.yaml
  977  oc adm policy add-scc-to-user spark-operator-scc -z spark-operator -n dev-spark-operator
  978  oc get po
  979  helm list
  980  helm uninstall spark-operator
  981  oc get sa spark -n dev-spark-operator
  982  oc adm policy add-scc-to-user spark-operator-scc -z spark -n dev-spark-operator
  983  helm list
  984  helm install spark-operator spark-kubernetes-operator/
  985  oc get po
  986  oc get events
  987  oc get po
  988  oc get deployment
  989  oc get po
  990  oc get deployment
  991  helm list
  992  vi spark-kubernetes-operator/templates/spark-operator.yaml
  993  oc get node
  994  oc projects
  995  oc get spark
  996  oc get pods
  997  oc get project spark
  998  oc project | grep spark
  999  oc project | grep dec-spark-operator
 1000  ls
 1001  cd spark
 1002  ls
 1003  nano spark.yaml
 1004  nano spark-service.yaml
 1005  cd
 1006  history
[epayuser@bastion ~]$
