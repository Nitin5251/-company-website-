
FROM nginx:alpine

LABEL maintainer="company"
LABEL description="Company Landing Page"

COPY index.html /usr/share/nginx/html/index.html
COPY style.css /usr/share/nginx/html/style.css

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
