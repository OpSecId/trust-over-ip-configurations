FROM ghcr.io/openwallet-foundation/acapy-agent:py3.13-1.5.1

RUN pip install \
  git+https://github.com/openwallet-foundation/acapy-plugins@1.5.1#subdirectory=rpc \
  git+https://github.com/openwallet-foundation/acapy-plugins@1.5.1#subdirectory=connections \
  git+https://github.com/openwallet-foundation/acapy-plugins@1.5.1#subdirectory=present_proof \
  git+https://github.com/openwallet-foundation/acapy-plugins@1.5.1#subdirectory=issue_credential
