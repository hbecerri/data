Files that serve as input for computing pile up weights. These have been generated using:

```bash
pileupCalc.py -i ../Cert_294927-306462_13TeV_EOY2017ReReco_Collisions17_JSON_v1.txt --inputLumiJSON pileup_latest.txt --calcMode true --minBiasXsec 69200 --maxPileupBin 100 --numPileupBins 100 nominal.root
pileupCalc.py -i ../Cert_294927-306462_13TeV_EOY2017ReReco_Collisions17_JSON_v1.txt --inputLumiJSON pileup_latest.txt --calcMode true --minBiasXsec 72383 --maxPileupBin 100 --numPileupBins 100 up.root
pileupCalc.py -i ../Cert_294927-306462_13TeV_EOY2017ReReco_Collisions17_JSON_v1.txt --inputLumiJSON pileup_latest.txt --calcMode true --minBiasXsec 66017 --maxPileupBin 100 --numPileupBins 100 down.root
```
