PUBLISH_HOST := publish.bashotechnologies.net

all:
	@jekyll --server

build:
	@jekyll

clean:
	@rm -rf _site

deploy publish: build
	@# Cover our ass
	@chmod 0600 .basho_blog_ssh_key
	rsync -vv -crlpD -e 'ssh -i .basho_blog_ssh_key' _site/ \
		basho@$(PUBLISH_HOST):/var/www/blog.basho.com/

.EXPORT_ALL_VARIABLES:
.PHONY: deploy publish clean
