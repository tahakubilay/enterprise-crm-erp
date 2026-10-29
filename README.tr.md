<div align="center">

# Enterprise CRM & ERP Platformu

### Müşteri operasyonları, iç iş akışları ve iş görünürlüğünü tek yapıda birleştiren platform

<img src="./assets/hero.svg" alt="CRM ve ERP proje görsel kimliği" />

<p><a href="./README.md">English</a> · <a href="./README.de.md">Deutsch</a> · <a href="./README.tr.md"><strong>Türkçe</strong></a></p>

<p>
  <a href="https://github.com/tahakubilay"><img src="https://img.shields.io/badge/Taha%20Kubilay-GitHub-181717?style=for-the-badge&logo=github" alt="Taha Kubilay GitHub" /></a>
  <a href="https://github.com/tahakubilay/enterprise-crm-erp"><img src="https://img.shields.io/badge/Repository-CRM%20%2F%20ERP-0A66C2?style=for-the-badge&logo=github" alt="Repository" /></a>
</p>

</div>

---

## Genel Bakış

Enterprise CRM & ERP Platformu, müşteri tarafındaki operasyonlarla iç iş süreçlerini ortak bir yönetim ortamında birleştirir.

Sistem; müşteri kayıtları, operasyonel workflow'lar, yönetim süreçleri ve raporlamanın farklı modüller arasında tutarlı kalabilmesi için ortak bir iş çekirdeği etrafında tasarlanmıştır.

## Problem

Birbirinden kopuk iş sistemleri genellikle şunlara yol açar:

- Tekrarlanan veya tutarsız kayıtlar
- Parçalı workflow'lar
- Manuel veri aktarımı
- Departmanlar arası düşük görünürlük
- Karmaşık raporlama
- Bağımsız süreçler arasında gereksiz sıkı bağlılık

## Mimari

```mermaid
flowchart LR
    CRM[Müşteri Domaini] --> CORE[Ortak İş Çekirdeği]
    ERP[ERP / Operasyonlar] --> CORE
    CORE --> RULES[İş Kuralları & Workflow'lar]
    CORE --> REPORTS[Raporlama & Yönetim Görünümleri]
    RULES --> DATA[(İş Verisi)]
    REPORTS --> DATA
```

## Temel Yetenekler

| Alan | Amaç |
|---|---|
| **Müşteri Yönetimi** | Müşteri ve ilişki bağlamını yönetmek |
| **Operasyonel Workflow'lar** | İç iş süreçlerini koordine etmek |
| **Ortak Veri Modeli** | İlgili bilgileri modüller arasında tutarlı tutmak |
| **Yetkilendirme** | Erişimi rol ve sorumluluğa göre ayırmak |
| **Raporlama** | Domainler arası operasyonel görünürlük sağlamak |
| **Yönetim Süreçleri** | İdari iş akışlarını merkezileştirmek |

## Mühendislik Odağı

Bu proje, CRM ve ERP yeteneklerinin tek bir ürün gibi çalışması gerektiğinde ortaya çıkan mimari problemlere odaklanır.

Başlıca konular:

- Domain ayrımı
- Ortak veri modelleme
- Modüller arası tutarlılık
- İş kuralı uygulama
- Workflow orkestrasyonu
- Yetkilendirme sınırları
- Raporlama mimarisi
- Uzun vadeli sürdürülebilirlik

## Veri & Gizlilik

Public repository production kimlik bilgileri, müşteri kayıtları, özel şirket verileri veya iç secret'lar içermez.

---

<div align="center">

### Geliştiren: [Taha Kubilay](https://github.com/tahakubilay)

`Enterprise Software` · `CRM` · `ERP` · `Workflow Design` · `Full-Stack Engineering`

</div>