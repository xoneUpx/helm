
#create private git repo for charts
helm repo index helm/ --url https://raspberrypi.tailb8113.ts.net:8443/gitea/bobok/helm
# add repo
helm repo add helm https://raspberrypi.tailb8113.ts.net:8443/gitea/bobok/helm
