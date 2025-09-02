# Kubernetes Intro for Advanced Users

## 🎯 Цель курса
Этот материал создан для разработчиков и инженеров, которые **работают с Kubernetes-кластером как пользователи**, а не как администраторы.  
После прохождения презентации слушатели должны уметь:
- легко ориентироваться в уже созданном кластере;
- быстро находить и анализировать основные сущности (Pods, Deployments, Services, Ingress);
- использовать удобные CLI-инструменты (`kubectl`, `k9s`);
- управлять приложениями через Helm и Helmfile.

Курс не требует знаний об администрировании Kubernetes (CNI, CSI, плагины и др.) — акцент только на **повседневной работе в существующем кластере**.

---

## 📚 Уровень курса
В обучающих материалах часто используется классификация уровней:
- **101** — самый вводный уровень (что такое Kubernetes, зачем он нужен).  
- **102** — продолжение 101, чуть глубже.  
- **201** — intermediate: практические навыки для уверенной работы.  
- **301+** — advanced: администрирование, internals, архитектура.

Данный курс соответствует уровню **201 — Advanced User**:  
он рассчитан на людей, которые уже знают, что такое Kubernetes, но хотят научиться **практически работать с ним каждый день**.

---

## 📝 Содержание презентации
- Основы: Pod → Deployment → Service → Ingress  
- Работа с `kubectl`  
- Навигация и поиск через `k9s`  
- Управление приложениями через Helm  
- Расширенное управление через Helmfile  

---

## 🚀 Как использовать
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/fedordikarev/k9s-intro-slides
   open index.html
   ```

## 🔗 Полезные ссылки
- [Kubernetes Docs](https://kubernetes.io/docs)  
- [kubectl cheatsheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)  
- [Helm Docs](https://helm.sh/docs)  
- [Helmfile Docs](https://helmfile.readthedocs.io)  
- [Katacoda Kubernetes Playground](https://www.katacoda.com/courses/kubernetes)  

---

💡 PR и улучшения приветствуются!
