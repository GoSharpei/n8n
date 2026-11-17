# Build from n8n's official image at the pinned version instead of
# re-implementing their install steps (the old npm -g install breaks on
# n8n >= 2.4x because of platform-specific native dependencies).
ARG N8N_VERSION
FROM n8nio/n8n:${N8N_VERSION}
