FROM ppiper/cf-cli:v11

# needed for cf to find its confi
# (GH resets HOME to /github/workspace)
ENV CF_HOME=$HOME
# RUN chmod +x /home/runner/work/cicdcheck/cicdcheck/.github/actions/cf-deploy
# COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT .github/actions/cf-deploy/entrypoint.sh
