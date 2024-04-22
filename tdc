import random

def generate_fake_news(theme):
    # Generate a fake news headline based on the specified theme
    headlines = {
        'health': ['Study finds shocking new cure for common cold!', 
                   'Scientists discover groundbreaking treatment for cancer!'],
        'politics': ['Breaking: Government announces major policy change!', 
                     'Political scandal rocks the nation!'],
        'technology': ['Tech giant unveils revolutionary new product!', 
                       'New technology promises to transform the way we live!']
    }

    if theme in headlines:
        headline = random.choice(headlines[theme])
        return headline
    else:
        return 'Invalid theme.'

def propagate_fake_news_on_social_networks(theme):
    # Generate fake news headline
    fake_news_headline = generate_fake_news(theme)
    
    # Pretend to post the fake news headline on social networks
    social_networks = ['Facebook', 'Twitter', 'Instagram']
    for network in social_networks:
        print(f'Posted fake news headline on {network}: {fake_news_headline}')

# Propagate fake news on social networks
propagate_fake_news_on_social_networks('technology')
