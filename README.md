# Integrator

This repository is wake up PSS.

## Start development

```sh
  git submodule init
  git submodule sync
  git submodule update
```

## Update submodule

```sh
  cd <PartnerAssistant | PersonalDataRepository | RecommendSystem>
  git checkout <Branch name>
  git pull
  cd ..
  git add <PartnerAssistant | PersonalDataRepository | RecommendSystem>
  git commit -m "Update submodule: <PartinerAssistant | PersonalDataRepository| RecommendSystem>"
```
