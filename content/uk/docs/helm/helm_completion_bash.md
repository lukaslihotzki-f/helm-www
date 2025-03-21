---
title: "Helm Completion Bash"
---

## helm completion bash

Генерація скрипта автодоповнення для bash

### Опис {#synopsis}

Генерація скрипта автодоповнення Helm для shell bash.

Для завантаження автодоповнень у вашій поточній shell-сесії:

```shell
source <(helm completion bash)
```

Для завантаження автодоповнень для кожної нової сесії, виконайте один раз:

- Linux:

  ```shell
  helm completion bash > /etc/bash_completion.d/helm
  ```

- MacOS:

  ```shell
  helm completion bash > /usr/local/etc/bash_completion.d/helm
  ```

```shell
helm completion bash [прапорці]
```

### Параметри {#options}

```none
  -h, --help              довідка для bash
      --no-descriptions   вимкнути описи автодоповнення
```

### Параметри, успадковані від батьківських команд {#options-inherited-from-parent-commands}

```
      --burst-limit int                 стандартні обмеження на стороні клієнта (стандартно 100)
      --debug                           вмикає розширений вивід
      --kube-apiserver string           адреса і порт сервера API Kubernetes
      --kube-as-group stringArray       група для імперсонації під час операції, цей прапорець може бути повторений для вказання кількох груп
      --kube-as-user string             імʼя користувача для імперсонації під час операції
      --kube-ca-file string             файл центру сертифікаці СА для підключення до сервера API Kubernetes
      --kube-context string             імʼя контексту kubeconfig для використання
      --kube-insecure-skip-tls-verify   якщо встановлено true, сертифікат сервера API Kubernetes не буде перевірятися на дійсність. Це робить ваші HTTPS-зʼєднання небезпечними
      --kube-tls-server-name string     імʼя сервера для перевірки сертифіката сервера API Kubernetes. Якщо не вказано, використовується імʼя хоста, що використовується для підключення до сервера
      --kube-token string               токен на предʼявника, який використовується для автентифікації
      --kubeconfig string               шлях до файлу kubeconfig
  -n, --namespace string                простір імен для цього запиту
      --qps float32                     кількість запитів в секунду під час взаємодії з API Kubernetes, не включаючи сплески
      --registry-config string          шлях до файлу конфігурації реєстру (стандартно "~/.config/helm/registry/config.json")
      --repository-cache string         шлях до теки, що містить кешовані індекси репозиторіїв (стандартно "~/.cache/helm/repository")
      --repository-config string        шлях до файлу, що містить імена та URL репозиторіїв (стандартно "~/.config/helm/repositories.yaml")
```

### ДИВИТИСЯ ТАКОЖ {#see-also}

- [helm completion](helm_completion.md) — генерувати скрипти автодоповнення для вказаного shell

###### Автоматично згенеровано spf13/cobra 11 вересня 2024
