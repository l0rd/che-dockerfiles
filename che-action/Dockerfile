# Copyright (c) 2016 Codenvy, S.A.
# All rights reserved. This program and the accompanying materials
# are made available under the terms of the Eclipse Public License v1.0
# which accompanies this distribution, and is available at
# http://www.eclipse.org/legal/epl-v10.html
#
# build:
#   docker build -t eclipse/che-dir .
#
# use:
#    docker run - /var/run/docker.sock:/var/run/docker.sock eclipse/che-action [command]

FROM eclipse/che-lib-typescript:nightly

ENTRYPOINT ["node", "/che-lib/index.js", "che-action"]
