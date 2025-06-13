# dpagent
# v1.2.9
zip -er dp-agent-config.zip dp-agent-config  -x "dp-agent-config/.git/* dp-agent-config/install-dogepool-agent/*" -P dogepool-67a5a3ba
mv dp-agent-config.zip dp-agent-1.2.9
zip -r dp-agent-1.2.9.zip dp-agent-1.2.9 -x "dp-agent/.git/*"
