# ViewNews
client for news viewing

- swift 5
- ios 12 (тільки iPhone, портретна орієнтація)
- використати UITableView (кастомна UITableViewCell повинна містити: source, author, title, description та імедж з urlToImage,  по кліку відкрити відповідну новину в SFSafariViewController), додати UIRefreshControl
- список посортований по publishedAt, обовязкова pagination, пошук
- запити до API винести в окремий клас
- фільтр по category/country/sources
