- 👋 Hi, I’m @AG-levelup8881188899
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
AG-levelup8881188899/AG-levelup8881188899 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
https://www.connect/login/oauth/authorize?redirect_uri=github%3A%2F%2Fcom.github.android%2Foauth&client_id=3f8b8834a91f0caad392&response_type=code&state=8INxS6G4i4pBgL6caf-U5w&nonce=PyxuCSLFm_1iQ2k8A1iN9Q&scope=user%20repo%20notifications%20admin%3Aorg%20read%3Adiscussion%20user%3Aassets%20project%20workflow&code_challenge=cI-fWe1fYVBifbu6J58Pyqf8wMFeywoVOQwi22lI4as&code_challenge_method=S256&allow_signup=false
https://iforms.americanexpress.com/iFormsSecure/un/iforms.do?cuid=acceptance_en_US&evtsrc=viewPage.submitButton&evttype=0
https://onlinebanking.aibgb.co.uk/inet/gb/login.htm
# Disable proxy
--on-proxy-server
---
apiVersion: mast.ansi.services/v1
kind: MastJob
metadata:
  name: git-basic-auth
  namespace: mast
spec:
  ansible:
    version: 2.9.18
  repository:
    git:
      url: https://github.com/smokaleksander/ansible_example.git
      credentials:
        basicAuth:
          usernameSecret:
            name: test-secret-basic-auth
            key: username
          passwordSecret:
            name: test-secret-basic-auth
            key: password
  configuration:
    playbook:
      - fromRepo:
          path: ansible-hello/playbook1.yaml
    vars:
      - fromRepo:
          path: ansible-hello/vars.yaml
    inventory:
      - fromRepo:
          path: ansible-hello/inventory

# Manual proxy address
--proxy-server=<scheme>=<uri>[:<port>][;...] | <uri>[:<port>] | "direct://"

# Manual PAC address
--proxy-pac-url=<pac-file-url>

# Disable proxy per host
--proxy-bypass-list=(<trailing_domain>|<ip-address>)[:<port>][;...]
https://1.1.1.1/dns/tls/ssl/cloudflare.com